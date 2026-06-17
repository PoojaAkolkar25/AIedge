pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building AIEdge application...'
            }
        }
        stage('Test') {
            steps {
                bat 'echo Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to staging...'
            }
        }
    }

