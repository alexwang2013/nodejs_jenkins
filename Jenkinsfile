pipeline {
    agent { docker { image 'node:16.13.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
                sh 'echo "Build Success"'
            }
        }
        stage('deploy') {
            steps {
                sh 'echo "Deployed"'
            }
        }
    }
}