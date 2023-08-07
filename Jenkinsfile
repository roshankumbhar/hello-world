pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 100, unit: 'SECONDS')
    }
    stages {
        stage('Example') {
            steps {
                echo 'Hello World from local workspace'
				        sh 'ls -la;pwd'
			    	
            }
        }
    }
}
