pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Example of a build command, such as:
                // sh './gradlew build'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example test command, like:
                // sh './gradlew test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Example deploy command, like:
                // sh './deploy.sh'
            }
        }
    }
}
