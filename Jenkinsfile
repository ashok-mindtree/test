pipeline {
  agent any
  stages {
    stage('code checkout') {
      steps {
        git(url: 'https://github.com/ashok-mindtree/test.git', branch: 'main')
      }
    }

    stage('Log') {
      steps {
        sh 'ls -a'
      }
    }

  }
}