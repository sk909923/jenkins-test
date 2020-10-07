pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat 'python calculator.py'
      }
    }
    stage('test') {
      steps {
        git 'python test.py'
      }   
    }
  }
}
