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
	    when
		    {
	
	 branch 'production'
			    {
			    echo 'bad'
			    }
		    }
	    }
    }
  }
