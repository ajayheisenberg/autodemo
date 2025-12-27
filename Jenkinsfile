pipeline {
    agent any  

    stages {
        stages {
        stage('Clone Code') {
            steps {
                git 'https://github.com/ajayheisenberg/autodemo.git'
            }
        }
        stage('Build') {
            steps {
                echo "Building the project..."
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deployment complete!"
            }
        }
    }
}
