pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/devikaMahesh/BlueOcean.git'
        bat 'make'
      }
    }
    stage('Deploy') {
      steps {
        echo 'deployed'
      }
    }
  }
}
