@Library('my-shared-library') _

pipeline{
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                script {
                    gitCheckout(
                        branch: "main",
                        url: "https://github.com/sus20/mrdevops_java_app.git"

                    )
                }
            }
        }

        stage('Unit Test maven') {
            steps {
                script {
                    mvnTest()
                }
            }
        }
    }
}
