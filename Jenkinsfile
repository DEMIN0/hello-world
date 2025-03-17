pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('build') {
            bat 'echo "hello world"'
            steps {
                bat 'npm --version'
            }
        }
    }
}