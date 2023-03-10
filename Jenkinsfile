pipeline {
    agent { docker { image 'python:3.10.7-alpine' } }
    stages {
        stage('build') {
            steps {
                echo 'Hello from first step'
                sh 'python --version'
            }
        }
    }
}