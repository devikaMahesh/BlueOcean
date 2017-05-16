pipeline {
  agent {
    node {
      label 'slave'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        echo 'Build took place'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deployed'
      }
    }
  }
}