pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        sh 'echo testing'
      }
    }

    stage('test') {
      steps {
        echo 'hello'
      }
    }

    stage('mvn') {
      steps {
        sh 'mvn package'
      }
    }

  }
}