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
                sh 'npm test'
            }
        }
    }
}
