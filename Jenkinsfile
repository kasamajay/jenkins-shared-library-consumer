@Library('ak-jenkins-shared-library') _

fullPipeline()

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'echo "Hello World" > hello.txt'
                sh 'printenv'
            }
        }
    }
}
