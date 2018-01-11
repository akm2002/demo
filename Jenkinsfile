pipeline {
  agent any
  stages {
    stage('UnitTest') {
      steps {
        sh 'mvn install'
        sh 'mvn test'
      }
    }
  }
}