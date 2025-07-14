pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage ('Test') {
      step {
        sh 'node --version'
      }
    }
  }
}
