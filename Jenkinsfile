pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello world!"'
      }
    }
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'How are you'
          }
        }
        stage('Parallel Stage ') {
          steps {
            echo 'This is to test Parallel stage'
          }
        }
      }
    }
  }
}