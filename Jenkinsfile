pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        bat(script: 'HelloWorld.java', label: 'hima')
      }
    }
  }
  environment {
    wnodws = ''
  }
}