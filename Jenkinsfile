pipeline {
    agent any

    stages {
        stage('verift Branch'){
            steps {
                echo "$GIT_BRANCH"
            }
        }
        stage('Docker Build'){
            steps {
                sh(script: 'docker compose build')
            }
        }
    }
}