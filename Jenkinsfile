pipeline {
    agent any

    environment {
        PATH = "/Applications/Docker.app/Contents/Resources/bin:/usr/local/bin:/opt/homebrew/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    }

    stages {
        stage('debug') {
            steps {
                sh 'echo $PATH'
                sh 'which docker'
                sh 'docker --version'
                sh 'docker info'
            }
        }
    }
}