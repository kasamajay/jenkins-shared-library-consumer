@Library('ak-jenkins-shared-library') _

fullPipeline([:]) {
  // The Eclipse libraries that our plugins depend unfortunately on required Java 11
  jdk = 'jdk_11_latest'
  extraMavenArguments = '-Pjacoco,pmd,run-rat-report'
}
