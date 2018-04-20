pipeline {
  agent any
  stages {
    stage('Stage 1') {
      parallel {
        stage('Stage 1') {
          steps {
            sh 'ls'
          }
        }
        stage('Stage 2') {
          steps {
            sleep 5
          }
        }
      }
    }
    stage('Stage 3') {
      steps {
        echo 'Hello'
      }
    }
    stage('stage 4') {
      steps {
        sh 'ls'
      }
    }
  }
}