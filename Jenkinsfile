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
        sh '/usr/bin/terraform init'
      }
    }

    stage('Teraform Plan') {
      steps {
        sh '/usr/bin/terraform plan'
      }
    }

    stage('Apply') {
      steps {
        sh '/usr/bin/terraform apply'
      }
    }

  }
}