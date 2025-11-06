pipeline {
    agent any

    environment {
        // Use the ENV_TYPE parameter to dynamically set the environment
        ENV_TYPE = dev
    }
    stages { // <--- This is the required 'stages' wrapper section
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the application...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}
