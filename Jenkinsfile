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
		options {
        timeout(time: 1, unit: 'HOURS')
	    }
		    stage('Example Deploy') {
            when {
               if(branch =='production'
		  {
                   echo 'Deploying'
		  }
		  else
		  {
			  echo 'Master'
		  }
            }
    }
  }
