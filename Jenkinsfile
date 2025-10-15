#this is Jenkinsfile
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building the project..."
                bat 'python app.py'
            }
        }
    }
}
