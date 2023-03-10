pipeline {
    agent {
        echo "Hello from agent"
     }
    stages {
        stage('build') {
            steps {
                echo 'Hello from first step'
                sh 'python --version'
            }
        }
    }
}