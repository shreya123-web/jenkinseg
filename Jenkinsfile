
pipeline {
    agent any

    stages {
        stage('Welcome') {
            steps {
                echo 'Hello from my first Jenkins Pipeline!'
                echo 'This is my first practical'
            }
        }

        stage('Check Environment') {
            steps {
                bat 'echo Jenkins is running on Windows'
                bat 'whoami'
            }
        }

        stage('Finish') {
            steps {
                echo 'Pipeline completed successfully!'
            }
        }
    }
}
