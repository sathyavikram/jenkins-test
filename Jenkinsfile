pipeline {
    agent {
        docker { image 'node:16.13.1-alpine' }
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Deploy - Staging') {
            steps {
                echo 'Deploy - Staging'
            }
        }
        stage('Deploy - Production') {
            steps {
                echo 'Deploy - Production'
            }
        }
    }
}