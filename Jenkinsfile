pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        echo 'Init'
        git(url: 'https://github.com/roperod/jenkins-test', branch: 'main')
      }
    }

  }
}