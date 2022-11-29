pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/Farhan-CSE/Donation-manangement-', branch: 'main')
      }
    }

    stage('Logs') {
      steps {
        sh 'tail -f /var/log/nginx'
      }
    }

  }
}