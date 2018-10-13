pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(quietPeriod: 5, job: 'account-service')
        build 'customer-service'
      }
    }
  }
  environment {
    Jenkinsfile = ''
  }
}