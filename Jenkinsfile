pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                script {
                    git branch: 'main', url: 'https://github.com/sus20/mrdevops_java_app.git'
                }
            }
        }
    }
}
