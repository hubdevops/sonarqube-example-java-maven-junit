pipeline {
  agent {
    docker {
      image 'alpine'
    }

  }
  stages {
    stage('error') {
      steps {
        build 'job1'
      }
    }
  }
}