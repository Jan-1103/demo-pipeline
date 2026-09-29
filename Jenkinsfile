pipeline {
    agent any
    stages {
        stage('Checkout SCM') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
               
                sh 'echo "Building the application..."'
            }
        }
        stage('Test') {
            steps {
               
                sh 'echo "Running tests..."'
            }
        }
        stage('Dockerize') {
            steps {
               
                sh 'docker build -t your-dockerhub-username/my-app:latest .'
                
                
            }
        }
        stage('Deploy') {
            steps {
               
                sh 'echo "Deploying to EC2 server..."'
               
            }
        }
    }
}
