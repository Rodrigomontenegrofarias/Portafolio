pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'npm install'
            }
            steps {
                sh 'npm start'
            }
        }
    }
}
