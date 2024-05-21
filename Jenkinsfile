pipeline {
    agent any
    
    tools {nodejs "NodeJS22"}

    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}