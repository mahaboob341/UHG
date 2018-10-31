pipeline {
  agent any
  stages {
    stage('Check out') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}