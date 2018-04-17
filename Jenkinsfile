pipeline {
  agent any
  stages {
    stage('SayHello') {
      steps {
        echo 'How are you doing?'
      }
    }
    stage('Java Version') {
      steps {
        sh 'java -version'
      }
    }
    stage('') {
      steps {
        sh 'echo ${PATH}'
      }
    }
  }
}