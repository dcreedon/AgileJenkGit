pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        powershell 'python --version'
        powershell(script: 'python server.py', returnStatus: true, returnStdout: true)
      }
    }

  }
}