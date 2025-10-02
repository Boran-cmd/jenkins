pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Holt den Code aus DEINEM Repo
                git branch: 'main',
                    url: 'https://github.com/Boran-cmd/jenkins.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
