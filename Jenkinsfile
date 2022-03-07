@Library('ak-jenkins-shared-library') _

fullPipeline()
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
