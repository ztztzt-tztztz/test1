pipeline {
  agent any
  stages {
    stage('buliding') {
      steps {
        sh 'ls -l'
        sh 'echo "start bulding"'
      }
    }

    stage('test') {
      steps {
        sh 'echo "start testing"'
      }
    }

    stage('deploy') {
      steps {
        sh 'start deployment'
      }
    }

  }
}