pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Serve HTML') {
            steps {
                bat 'python3 -m http.server 8181'
            }
        }
    }
}
