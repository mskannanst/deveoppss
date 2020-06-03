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
		    steps{
		     sh 'echo "SSH private key is located at $SSH_CREDS"'
                sh 'echo "SSH user is $SSH_CREDS_USR"'
                sh 'echo "SSH passphrase is $SSH_CREDS_PSW"'
		    }}
    }
  }
