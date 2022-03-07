@Library('ak-jenkins-shared-library') _

pipeline {
    agent { label any }
    stages {
        stage('checkout') {
            steps {
                fullPipeline()
            }
        }
    }
}
