pipeline {
  agent any
  stages {
    stage('Check out Repo') {
      steps {
        git(url: 'https://github.com/rajavenkatesh/bookstore.git', branch: 'master', poll: true, credentialsId: 'github')
      }
    }

  }
}
