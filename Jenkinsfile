pipeline {
  agent any
  triggers {
    cron('H/15 * * * *')
  }
  stages {
    stage('Check Out code .....') {
      steps {
        git(url: 'https://github.com/rajavenkatesh/bookstore.git', branch: 'master', poll: true, credentialsId: 'github')
      }
    }

  }
}
