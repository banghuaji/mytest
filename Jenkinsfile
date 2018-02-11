pipeline {
  agent any
  stages {
    stage('say hello') {
      parallel {
        stage('say hello') {
          steps {
            sleep 60
          }
        }
        stage('say good bye') {
          steps {
            sleep 60
          }
        }
      }
    }
  }
}