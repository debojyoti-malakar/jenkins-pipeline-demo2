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
        echo 'Building application!'
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
