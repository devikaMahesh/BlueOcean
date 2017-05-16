pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/devikaMahesh/BlueOcean.git'
        sh 'mvn complie'
      }
    }
    stage('Deploy') {
      steps {
        echo 'deployed'
      }
    }
  }
}