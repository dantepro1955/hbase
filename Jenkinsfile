pipeline {
  agent any
  stages {
    stage('S1') {
      parallel {
        stage('S1') {
          steps {
            echo 'asdasdasds'
          }
        }
        stage('') {
          steps {
            dir(path: '/home')
          }
        }
        stage('') {
          steps {
            sleep 1
          }
        }
      }
    }
  }
}