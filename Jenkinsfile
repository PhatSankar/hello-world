pipeline {
    agent any 
    tools {
        nodejs '16.10.0'
    }
    stages {
        stage('Node version') { 
            steps {
                sh 'npm version'
            }
        }
    }
}