pipeline {
  agent any
  stages {
    stage('Check for Terraform Version') {
      steps {
        sh '/usr/bin/terraform -version'
      }
    }

  }
}