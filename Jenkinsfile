pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hellow World!'
        sh 'java -version'
      }
    }
  }
}