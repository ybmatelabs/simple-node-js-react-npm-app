pipeline {
  agent {
    node {
      label '6'
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