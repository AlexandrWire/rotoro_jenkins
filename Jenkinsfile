pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        sh 'go test ./...'
      }
    }

  }
  environment {
    GO111MODULE = 'on'
  }
}