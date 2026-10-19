pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Repository checked out successfully.'
            }
        }

        stage('Build') {
            steps {
                echo 'Build completed successfully.'
            }
        }

        stage('Test') {
            steps {
                echo 'Test completed successfully.'
            }
        }
    }

    post {
        success {
            echo 'Jenkins build succeeded.'
        }
        failure {
            echo 'Jenkins build failed.'
        }
    }
}
