pipeline {
    agent any
    
    tools {nodejs "NodeJS22"}

    stages {
        
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
        
        stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }

    }
}