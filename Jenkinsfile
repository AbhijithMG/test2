pipeline {
  agent any
  stages {
    stage('code') {
      steps {
        git(url: 'https://github.com/AbhijithMG/test2.git', branch: 'main', changelog: true)
      }
    }

  }
}