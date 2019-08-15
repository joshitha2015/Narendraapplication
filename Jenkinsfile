pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        bat(script: 'https://github.com/joshitha2015/Narendraapplication.git', label: 'dev', returnStatus: true, returnStdout: true)
      }
    }
  }
}