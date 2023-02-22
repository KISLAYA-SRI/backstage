pipeline {
    agent any
    stages {
	// Echo
	stage('Publish message') {
	    steps{
               sh '''
		      while true
		      do
			echo "Hello World! ${key}"
		      done
                  '''
            }
	}
   }
}
