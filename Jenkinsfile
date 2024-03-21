pipeline {
  agent {label 'linux'}
  
  stages {
    stage('Build') {
      steps {
        sh echo 'building the multistage'
      }
    }
    stage('test') {
      steps {
        sh echo 'testing the app'
      }
    }
    stage('test') {
      steps {
        sh echo 'deploy the app'
      }
    }
  }
}
