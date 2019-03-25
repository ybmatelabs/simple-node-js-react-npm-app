pipeline {
  agent {
    node {
      label 'H20'
    }

  }
  stages {
    stage('build') {
      agent any
      steps {
        sh 'npm install'
      }
    }
  }
}