pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn integration-test -Dmain-suite=\${circuit-suite}'
      }
    }
    stage('Deploy') {
      steps {
        echo 'deployed'
      }
    }
  }
}