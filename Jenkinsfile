pipeline {
    agent {
        docker {
            image 'node:10-alpine' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Install') { 
            steps {
                sh 'yarn install' 
            }
        }
        stage('Build') { 
            steps {
                sh 'yarn build' 
            }
        }

    }
}
