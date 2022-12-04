pipeline {
  agent any
 
  tools {nodejs '19.2.0'}
 
  stages {
    stage('Example') {
      steps {
        sh 'npm install'
      }
    }
    stage('deploy') {
      steps {
        sh 'npm start'
      }
    }
  }
}
