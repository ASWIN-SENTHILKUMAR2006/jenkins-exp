pipeline{
    agent any
    stages{
        stage('Checkout code') {
            steps {
                // Checkout the code from the repository
                sh"sample project fetch from git"
            }
        }
        stage('Build'){
            steps{
                sh"Building bricks"
        }
        }
        stage('Deployement'){
            steps{
                sh"Deploying"
            }
        }
    }
}
