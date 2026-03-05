pipeline {
    agent any
    
    tools {
        // Ensure this name matches your Maven name in Manage Jenkins -> Tools
        maven 'maven' 
    }

    stages {
        stage('Build & Test') {
            steps {
                // Use 'bat' instead of 'sh' for Windows
                bat 'mvn clean test'
            }
        }
    }
}
