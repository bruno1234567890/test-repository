pipeline {
  agent {
    node {
      label 'Deploy'
    }
    
  }
  stages {
    stage('') {
      steps {
        build 'test1'
      }
    }
  }
  environment {
    QA_INT = 'http://qa.qvc.com/'
  }
}