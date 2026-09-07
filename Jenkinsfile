pipeline {
  agent any 
  stages {
    stage('Checkout') {
      steps {
        echo 'Checking application!'
      }
    }
    stage('Build') {
      steps {
        echo 'Building application Version-99!'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing application!'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying application!'
      }
    }
  }
  post {
    success {
      echo 'BUILD SUCCESSFUL!'
    }
    failure {
      echo 'BUILD FAILED!'
    }
  }
}
