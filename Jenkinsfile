pipeline {
    agent {
        sh 'echo "Hello from agent"'
     }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello from first step"'
                sh 'python --version'
            }
        }
    }
}