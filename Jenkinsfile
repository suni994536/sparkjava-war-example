pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo stage1'
      }
    }
    stage('build the prject') {
      steps {
        sh 'mvn clean'
      }
    }
  }
}