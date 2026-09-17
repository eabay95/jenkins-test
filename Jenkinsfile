pipeline {
    agent {
        docker {
            image 'maven:3.9.16-eclipse-temurin-21-alpine'
        }
    }

    environment {
        PATH = "/Applications/Docker.app/Contents/Resources/bin:/usr/local/bin:/opt/homebrew/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    }

    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}