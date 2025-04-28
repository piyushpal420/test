pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/piyushpal420/test.git'
            }
        }
        stage('List Files') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
