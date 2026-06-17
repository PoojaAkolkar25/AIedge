pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building AIEdge application...'
            }
        }
        stage('Test') {
            sh 'npm test' // Syntax Error: sh outside steps block!
        }
    }
}
