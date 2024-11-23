pipeline {
  agent {
    node {
      label 'win-agent'
    }

  }
  stages {
    stage('clean') {
      steps {
        bat 'mvn - DskipTest clean'
      }
    }

    stage('compile') {
      steps {
        bat 'mvn - Dskiptest compile'
      }
    }

  }
}