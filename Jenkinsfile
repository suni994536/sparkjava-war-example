pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'sh \'echo stage1\''
      }
    }
    stage('build the prject') {
      steps {
        sh 'sh \'mvn clean\''
      }
    }
  }
}