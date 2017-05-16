pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/devikaMahesh/BlueOcean.git'
        bat 'mvn clean install'
        readFile 'pom.xml'
      }
    }
    stage('Deploy') {
      steps {
        echo 'deployed'
      }
    }
  }
}