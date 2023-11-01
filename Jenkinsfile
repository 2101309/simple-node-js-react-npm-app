pipeline {
    agent {
        docker {
            image 'node:20.9.0-alpine3.18' 
            args '-u 1000:1000' 
            port 3000:3000
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}

