pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */

   pipeline {
        agent any
        stages {
            stage('Build') {
                ./gradlew assemble
            }
            stage('Test') {
                ./gradlew test
            }
        }
   }
}
