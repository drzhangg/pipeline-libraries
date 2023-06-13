@Library("github-libraries") _
def tools = new org.devops.tools()

hello()

pipeline {
    agent any

    stages {
        stage ("GetCode") {
            steps{
                script {
                    tools.PrintMes("test tools printmes1.")
                }
            }
        }
    }
}