pipeline {
    agent any

    environment {
        ENV = 'production'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build steps here
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your test steps here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deploy steps here
            }
        }
    }

    post {
        always {
            echo 'Sending notifications...'
            // Add your notification steps here (e.g., email-ext or slack)
        }
    }
}
