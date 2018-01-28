pipeline {
  agent {
    node {
      label 'node:6-alpine'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}