pipeline {
  agent any
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