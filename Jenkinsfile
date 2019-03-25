pipeline {
  agent {
    node {
      label 'H20'
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