pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Holt den Code aus deinem Repo
                git branch: 'main',
                    url: 'https://github.com/DEIN-USER/DEIN-REPO.git'
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

