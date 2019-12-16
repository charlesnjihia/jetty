pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                // Download the code
                checkout scm
                
            }
        }
        stage('Test') {
            steps {
                echo "test on multibranching pipeline"
            }
        }
    }
	post {
        always {
            // Report test results
            echo "We got to the post section"
        }
    }
}
