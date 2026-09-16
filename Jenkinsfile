pipeline {
  agent {
    label 'ubuntu-agent'
  }
  stages {
    stage("Build") {
      steps {
        sh 'echo Building...'
      }
    }
    stage('Test') {
      steps {
        sh 'echo Testing'
      }
    }
  }
}
