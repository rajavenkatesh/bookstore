pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        git(url: 'https://github.com/rajavenkatesh/bookstore.git', branch: '.', poll: true, credentialsId: 'github')
      }
    }

  }
}