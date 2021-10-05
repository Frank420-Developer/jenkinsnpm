pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-u root -p 3000:3000'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Corriendo el programa'
        sh 'npm install'
      }
    }

  }
}