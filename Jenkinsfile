pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Code fetched from GitHub'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t devops-demo .'
            }
        }

        stage('Verify Image') {
            steps {
                sh 'docker images'
            }
        }
    }
}
