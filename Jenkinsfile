pipeline {
    agent any

    stages {
        stage('NPM Install') {
            steps {
                sh 'npm install'
            }
        }
        stage('NPM Run Tests') {
            steps {
                sh 'npm run test'
            }
        }        
    }
}