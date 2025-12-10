pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building the project..."
                bat 'dir'  // Windows equivalent of 'ls -la'
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying..."
            }
        }
    }
}
