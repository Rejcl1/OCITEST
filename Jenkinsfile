pipeline {
  agent any
  stages {
    stage('Check for Terraform Version') {
      steps {
        sh '/usr/bin/terraform -version'
      }
    }

    stage('Terraform Init') {
      steps {
        sh '/usr/bin/terraform -init'
      }
    }

  }
}