pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo "Code downloaded successfully!"
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
                sh 'echo "Hello from GitHub!"'
            }
        }
    }
}
