pipeline {
  agent none
  stages {
    stage('Build') {
      agent any
      steps {
        sh 'yarn install --production'
      }
    }
  }
}
