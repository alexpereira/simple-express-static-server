pipeline {
    agent { docker { image 'node:8.7' } }
    stages {
        stage('build') {
            steps {
                sh 'npm start'
            }
        }
    }
}
