pipeline {
    agent {
      label 'linux-node'

    stages {

        stage('Checkout') {
            steps {
                echo "Checking out source code..."
            }
        }

        stage('Build') {
            steps {
                echo "Building the application..."
                sh 'echo Build Successful'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                sh 'echo Test Successful'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
                sh 'echo Deployment Successful'
            }
        }
    }

    post {
        success {
            echo "Pipeline executed successfully."
        }

        failure {
            echo "Pipeline execution failed."
        }
    }
}
