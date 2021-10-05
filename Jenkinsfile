pipeline {
  agent {
    any {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Corriendo el programa'
        sh '/usr/bin/npm install'
      }
    }

  }
}