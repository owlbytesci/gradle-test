pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'gradle clean gradle assemble'
      }
    }
  }
}