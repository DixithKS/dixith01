pipeline {
  agent any
  stages {
    stage('build_app') {
      steps {
        sh 'echo "this is build stage running on 'hostname' host!"'
      }
    }
    stage('app_testing') {
      steps {
        sh 'echo "this is test stage running on 'hostname' host!"'
      }
    }
  }
}
