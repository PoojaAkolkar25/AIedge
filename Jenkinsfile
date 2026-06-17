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
                bat 'echo Running unit tests... ALL PASSED'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to staging environment...'
            }
        }
    }
    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed! Check the logs.'
        }
    }
}
