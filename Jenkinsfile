pipeline {
    agent any

    stages {
        stage('Build Frontend') {
            steps {
                sh 'echo building frontend'
                sh 'cd frontend && npm i && npm run build'
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
