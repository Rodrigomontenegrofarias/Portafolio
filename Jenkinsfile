pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
            steps {
                sh 'npm start'
            }
        }
    }
}
