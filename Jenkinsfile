pipeline {
  agent {
    node {
      label 'utility-slave'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        echo 'Pretend Building...'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing...'
        sh '''ls -la
echo "================="
pwd'''
      }
    }
    stage('TestMore') {
      steps {
        echo 'More tests'
      }
    }
  }
}