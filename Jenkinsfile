pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building AIEdge application...'
            }
        }
        stage('Test') {
            bat 'echo Running tests...'
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to staging...'
            }
        }
    }
}
