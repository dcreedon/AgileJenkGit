pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        powershell 'python --version'
        powershell 'python helloworld.py'
      }
    }

    stage('Test') {
      steps {
        timestamps()
        echo 'Testing'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

  }
}