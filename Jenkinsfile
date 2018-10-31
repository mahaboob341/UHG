pipeline {
  agent any
  stages {
    stage('Check out') {
      parallel {
        stage('Check out') {
          steps {
            sh 'mvn clean install'
          }
        }
        stage('QA') {
          steps {
            bat 'dev'
          }
        }
      }
    }
  }
}