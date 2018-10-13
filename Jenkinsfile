pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'account-service', quietPeriod: 5)
      }
    }
  }
}