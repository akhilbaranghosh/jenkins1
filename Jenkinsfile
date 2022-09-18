pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/akhilbaranghosh/jenkins1', branch: 'master')
      }
    }

    stage('Build') {
      steps {
        sh 'java src/Main.java'
      }
    }

  }
}