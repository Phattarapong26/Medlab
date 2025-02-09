pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Phattarapong26/Medlab.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building Project..."'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running Tests..."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying Project..."'
            }
        }
    }
    post {
        always {
            echo "Pipeline finished"
        }
    }
}
