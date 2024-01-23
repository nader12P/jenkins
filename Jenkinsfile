pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Check out the source code from your version control system (e.g., Git)
                sh 'docker build -t docker.io/nader12bp/new-app'
            }
        }
}

