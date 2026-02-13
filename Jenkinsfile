pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code...'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building project'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Running tests'
            }
        }
    }
}
