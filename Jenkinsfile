pipeline {
  agent any
  stages {
    stage('docker') {
      steps {
        build(job: 'build1', quietPeriod: 2)
      }
    }
  }
}