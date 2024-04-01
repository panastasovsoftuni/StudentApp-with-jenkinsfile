pipeline {
    agent any

    stages {
        stage('NPM Install') {
            steps {
                sh 'npm install'
            }
        }

        stage('NPM Audit') {
            steps {
                sh 'npm audit'
            }
        }  
        stage('Run Integration Tests') {
            steps {
                sh 'npm run test'
            }
        }        
    }
}