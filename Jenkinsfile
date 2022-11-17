pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        echo 'Starting Init Stage'
        git(url: 'https://github.com/roperod/jenkins-test', branch: 'main')
      }
    }

    stage('Python Version') {
      steps {
        sh '''echo "Python Version: "
python3 -V'''
      }
    }

    stage('Check Files') {
      steps {
        sh 'ls -l'
      }
    }

  }
}