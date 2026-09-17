pipeline {
    agent any

    stages {
        stage('debug') {
            steps {
                sh 'echo $PATH'
                sh 'which docker || true'
                sh 'docker --version'
            }
        }
    }
}