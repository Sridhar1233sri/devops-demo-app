pipeline {
    agent any

    stages {
        stage('GitHub Checkout') {
            steps {
                echo 'Code pulled from GitHub successfully!'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment successful!'
            }
        }
    }
}
