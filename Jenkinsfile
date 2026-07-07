pipeline {
    agent {
        label 'linux-node'
    }

    stages {
        stage('checkout'){
            steps {
                echo "checkout source code"
            }
        }

        stage('Build') {
            steps {
                echo "Build stage"
            }
        }

        stage('Test') {
            steps {
                echo "Test stage"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy stage"
            }
        }
    }

    post {
        success {
            echo "All stages completed successfully!"
        }

        failure {
            echo "Pipeline execution failed."
        }

        always {
            echo "Pipeline execution finished."
        }
    }
}
