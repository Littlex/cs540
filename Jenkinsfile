pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        build(job: 'job1', propagate: true, wait: true)
      }
    }
  }
}