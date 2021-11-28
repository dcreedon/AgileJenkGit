pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        powershell 'python --version'
        powershell(script: 'python helloworld.py', returnStatus: true, returnStdout: true)
      }
    }

  }
}