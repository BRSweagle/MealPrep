pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        build(job: 'Job1', quietPeriod: 5, wait: true)
      }
    }
  }
}