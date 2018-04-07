pipeline {
    agent { docker { image 'node:8.7' } }
    stages {
        stage('build') {
            steps {
                sh 'npm install'
            }
        }
        stage('test') {
           steps {
               sh 'npm test'
           }
        }
        stage('start') {
           steps {
               sh 'npm start'
           }
        }
    }
}
