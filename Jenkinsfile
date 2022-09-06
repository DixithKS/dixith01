pipeline {
  agent any
  stages {
    stage('build_app') {
      steps {
        sh 'echo "this is build stage by ${NAME} user!"'
      }
    }
    stage('app_testing') {
      steps {
        sh 'echo "this is test stage!"'
      }
    }
  }
}
