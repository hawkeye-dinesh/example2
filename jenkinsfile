pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Cloning repository...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
                bat 'echo Build successful'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo Tests passed'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying project...'
                bat 'echo Deployment completed'
            }
        }
    }
}
