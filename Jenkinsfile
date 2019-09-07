pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'echo $PATH'
                sh 'echo "Hello from Docker Container"'
            }
        }
    }
}
