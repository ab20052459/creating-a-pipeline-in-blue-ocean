pipeline {
  agent {
    docker {
      image 'node:6-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install --registry=https://registry.npm.taobao.org'
      }
    }

  }
}