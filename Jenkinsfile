pipeline {
    agent { label "nodejs"}

    stages {
        stage ("npm") {
            steps {
                sh "npm -version"
                sh "node --version"
                sh "npm install"
            }
        }
    }
}
