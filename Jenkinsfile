pipeline {
  agent {
    label 'jdk8'
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