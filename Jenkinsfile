pipeline {
  agent {
    docker {
      image 'maven:3.3.9-jdk-8'
      args '-v /root/.m2:/root/.m2'
    }

  }
  stages {
    stage('Initialize') {
      steps {
        echo 'this is minimal pipeline'
      }
    }

  }
}