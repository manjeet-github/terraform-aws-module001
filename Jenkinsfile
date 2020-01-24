pipeline {
  agent {
    node {
      label 'node'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Building'
      }
    }
    stage('Test') {
      steps {
        echo 'testing'
      }
    }
    stage('Deploy') {
      steps {
        echo 'deploy'
      }
    }
  }
  environment {
    ENV1 = 'VALUE1'
  }
}