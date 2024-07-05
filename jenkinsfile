pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building branch ${env.BRANCH_NAME}"
                // Build steps
            }
        }
        stage('Test') {
            steps {
                echo "Testing branch ${env.BRANCH_NAME}"
                // Test steps
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying branch ${env.BRANCH_NAME}"
                // Deploy steps
            }
        }
    }
}
