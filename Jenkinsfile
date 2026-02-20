pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        git branch: 'main',
            https://github.com/kimjaeyoung/sample-app.git
      }
    }

    stage('Build') {
      steps {
        echo 'Build step (placeholder)'
      }
    }

    stage('Test') {
      steps {
        echo 'Test step (placeholder)'
      }
    }
  }
}