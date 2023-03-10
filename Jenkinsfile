pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello from first step"'
                sh 'echo $JAVA_HOME'
            }
        }
        stage('deploy') {
            steps {
                sh 'echo "Hello from second step"'
                sh 'python --version'
            }
        }
    }
}