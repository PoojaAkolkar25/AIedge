pipeline {
    agent any
    tools {
        git '''C:\Program Files\Git\bin\git.exe'''
    }
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
}