pipeline {
    agent { docker {image "node:10"}}

    stages {
        stage ("npm") {
            steps {
                sh "npm install"
            }
        }
    }
}
