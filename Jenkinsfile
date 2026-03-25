pipeline {
    agent { label 'slave2' }
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'echo "Building the application..."'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'echo "Running tests..."'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sh 'echo "Deploying the application..."'
                sh 'echo "test"'
            }
        }
    }
}
