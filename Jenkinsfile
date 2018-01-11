pipeline {
  agent any
  stages {
    stage('UnitTest') {
      steps {
        hygieiaBuildPublishStep(buildStatus: 'success')
        sh 'mvn clean install'
        sh 'mvn test'
      }
    }
  }
}