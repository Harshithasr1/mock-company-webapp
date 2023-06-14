pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
agent any

  stages {
    stage('Build') {
      steps {
        // Build step examples
         sh './gradlew assemble'     // Execute shell command
      }
    }

    stage('Test') {
      steps {
        // Test step examples
        sh './gradlew test'         // Execute shell command
      }
    }
  }

}
