pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/piyushpal420/test.git'
            }
        }
        stage('List Files') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
