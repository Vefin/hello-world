pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World!'
            }
        }
        stage('Show node version') {
            steps {
                bat "node --version"
            }
        }
    }
}