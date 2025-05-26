// Jenkinsfile
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application from Git...'
                // In a real scenario, you'd run build commands here (e.g., mvn clean install)
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests from Git...'
                // In a real scenario, you'd run test commands here (e.g., mvn test)
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application from Git...'
                // In a real scenario, you'd run deployment commands here
                echo "Hello, Jenkins Pipeline from Git!"
            }
        }
    }
}