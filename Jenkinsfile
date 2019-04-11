pipeline {
  agent any
  stages {
    stage('Test') {
      agent {
        docker {
          image 'maven:3-jdk-8-alpine'
        }

      }
      steps {
        sh 'mvn test'
      }
    }
  }
}