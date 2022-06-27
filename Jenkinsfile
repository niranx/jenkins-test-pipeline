pipeline {
    agent { docker { image 'node:16.15.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version \
                ls -la'
            }
        }
    }
}
