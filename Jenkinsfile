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
		}
	}
	    stage('three')
	    {
	    steps
		    {
	 if(branch=='production')
			    {
			    echo 'bad'
			    }
		else
		{
		echo 'good'
		}
		    }
	    }
    }
  }
