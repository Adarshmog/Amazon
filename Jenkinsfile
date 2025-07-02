pipeline {
    agent { label 'windows_slave' }

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/Adarshmog/Amazon.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
