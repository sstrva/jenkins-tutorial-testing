pipeline {
    agent { docker { image 'openjdk:16-alpine3.13' } }
    stages {
        stage('build') {
            steps {
                sh 'java --version'
            }
        }
    }
}
