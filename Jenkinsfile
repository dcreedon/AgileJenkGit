pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('build') {
            steps {
            echo 'Building'
                sh 'python --version'
            }
        }
        stage('Test') {
            steps {
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