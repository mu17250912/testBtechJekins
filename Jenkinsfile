pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/mu17250912/testBtechJekins.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo Building the application...'
            }
        }
        stage('Test') {
            steps {
                sh 'echo Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo Deploying application...'
            }
        }
    }
}
