pipeline {
    agent any
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
    } // <--- End of 'stages' section
}
