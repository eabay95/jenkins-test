pipeline {
    agent {
        docker {
            image 'maven:3.9.16-eclipse-temurin-21-alpine'
        }
    }

    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}