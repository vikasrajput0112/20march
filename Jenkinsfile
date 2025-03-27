pipeline {
    agent any

    stages {
        stage('List Files') {
            steps {
                script {
                    // Correct way to use shell commands in Jenkinsfile
                    sh 'ls -l'
                }
            }
        }

        // Other stages can go here, e.g., Build, Test, Deploy
    }
}
