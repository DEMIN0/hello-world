pipeline {
    agent any
    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE    = 'sqlite'
    }

    stages {
        stage('build') {
            steps {
               echo 'Starting build stage...'
               bat 'set'
                echo 'Finished build stage.'

            }
        }
    }
}