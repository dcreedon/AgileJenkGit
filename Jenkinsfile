pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        powershell 'python --version'
        powershell 'python helloworld.py'
        echo 'Building'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing'
        powershell 'python helloworld.py'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
        powershell 'python helloworld.py'
        powershell 'python --version'
      }
    }

  }
}