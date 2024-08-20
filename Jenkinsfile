pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo Building'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Testing'
            }
        }

        stage('TestGitWebhook') {
            steps {
                sh 'echo Git Webhook works'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo Deploying'
            }
        }
    }
}
