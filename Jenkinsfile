pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Command to build the application
                sh './gradlew assemble'
            }
        }
        stage('Test') {
            steps {
                // Command to run tests
                sh './gradlew test'
            }
        }
    }
}
