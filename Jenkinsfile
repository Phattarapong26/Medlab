pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo "Clone Code the project From Git"
            }
        }
        stage('Build') {
            steps {
                echo "Building the project..."
            }
        }

        stage('Unit Tests') {
            steps {
                echo "Running tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the application..."
            }
        }
        stage('Deployment test') {
            steps {
                echo "Running tests..."
            }
        }
    }
}
