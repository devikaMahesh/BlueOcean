pipeline {
  agent {
    node {
      label 'slav1'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        fileExists 'BlueOcean Integration'
      }
    }
    stage('Test') {
      steps {
        echo 'Test is done'
      }
    }
    stage('Deploy') {
      steps {
        echo 'deployed'
      }
    }
  }
}