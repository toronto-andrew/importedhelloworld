pipeline {
  agent {
    docker {
      image 'gradle:6.7-jdk11'
    }

  }
  stages {
    stage('step1') {
      steps {
        sh 'gradle --version'
      }
    }

  }
}