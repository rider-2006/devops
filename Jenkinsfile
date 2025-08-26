pipeline {
    agent any
    
    stages {
        stage('Clone') {
            steps {
                // Cloning the repository from GitHub
                git branch: 'main', url: 'https://github.com/rider-2006/devops.git'
            }
        }
        
        stage('Build') {
            steps {
                // Replace this with your actual build command
                echo 'Building the application'
            }
        }
    }
}
