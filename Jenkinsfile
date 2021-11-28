pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        powershell 'python --version'
        powershell 'python helloworld.py'
      }
    }

  }
}