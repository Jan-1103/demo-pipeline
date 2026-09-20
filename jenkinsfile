pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out source code...'
            }
        }
        stage('Build Docker Image') {
            steps {
                echo 'Building Docker image...'
                
            }
        }
        stage('Login & Push') {
            steps {
                echo 'Logging into Docker Hub and pushing image...'
              
            }
        }
    }
    post {
        always {
            echo 'Pipeline execution completed!'
        }
    }
}
