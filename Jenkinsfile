pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        bat(script: 'https://github.com/joshitha2015/Narendraapplication.git', label: 'dev', returnStatus: true, returnStdout: true)
      }
    }
    stage('build') {
      steps {
        bat 'mvn deploy'
      }
    }
    stage('sonarcube') {
      steps {
        echo 'sonarcube'
      }
    }
    stage('test') {
      steps {
        echo 'test'
      }
    }
  }
}