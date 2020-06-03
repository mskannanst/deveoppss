pipeline {
    agent any
    stages {
        stage('one') {
            steps {
                echo 'Hello World'
            }
        }
		stage('two')
		{
		steps
		{
		echo 'second stage'
			sleep time:250 , unit: 'NANOSECONDS'
		}
			
	}
	    stage('three')
	    {
	    steps
		    {
		    echo 'bad'
		    echo 'good'
		    }
   }
	    
	    stage('four')
	    {
	     parameters {
        string(name: 'PERSON', defaultValue: 'Kannan', description: 'Who should I say hello to?')
	     
	steps
		    {
		    echo "Hello ${params.PERSON}"
		    }  
	     }
    }
  }
}
