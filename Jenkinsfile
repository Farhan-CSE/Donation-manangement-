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
        sh 'ls -lh'
      }
    }

    stage('Git pull') {
      steps {
        sh 'service nginx status'
      }
    }

  }
}