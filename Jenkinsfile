pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "building the multistage"'
                // Add your build steps here
            }
        }
        stage('Test') {
            steps {
                sh 'echo "testing the app"'
                // Add your test steps here
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "deploy the app"'
                // Add your deployment steps here
            }
        }
    }
}

