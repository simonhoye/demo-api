pipeline {
    agent { docker { image 'node:8.9.0' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}