pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'Echo "Building"'
      }
    }

    stage('Deploy') {
      steps {
        bat 'Echo "Deploying"'
      }
    }

    stage('Test') {
      steps {
        bat 'Echo "Testing"'
      }
    }

    stage('Release') {
      steps {
        bat 'Echo "Releasing to App Server"'
      }
    }

  }
}