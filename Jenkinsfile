pipeline {
  agent any
  triggers {
   // cron('H/15 * * * *')
    githubPush()  // github webhook push
  }
  stages {
    stage('Check out Repo-----check pull request') {
      steps {
        git(url: 'https://github.com/rajavenkatesh/bookstore.git', branch: 'master', poll: true, credentialsId: 'github')
      }
    }

  }
}
