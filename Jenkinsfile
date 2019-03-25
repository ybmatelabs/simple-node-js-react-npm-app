pipeline {
  agent {
    node {
      label 'linux'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }
  }
}