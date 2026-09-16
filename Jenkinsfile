pipeline {
  agent {
    label 'ubuntu-agent'
  }
  stages {
    stage("Code") {
      steps {
        sh 'echo this is cloning the code'
        git url: "https://github.com/LondheShubham153/django-notes-app.git", branch: "main"
        echo "code clonning succssfully'
      }
    }
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
