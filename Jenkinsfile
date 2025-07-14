pipeline {
  agent {
    docker { image 'node:alpine3.22' }
  }
  stages {
    stage ('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}
