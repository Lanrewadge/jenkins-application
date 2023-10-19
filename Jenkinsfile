pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Pull the code from your Git repository
                checkout scm
            }
        }
        stage('Build and Deploy') {
            steps {
                // Execute any build or deployment steps you need here
                sh 'python app.py &'
            }
        }
    }
}
