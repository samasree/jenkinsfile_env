pipeline {
  agent any
  stages {
    stage('Build') {
      environment {
        Name='name'
      }
      steps {
        echo "${env.BUILD_ID}, ${env.JENKINS_URL}, ${env.Name}"
      }
    }
  }
}
