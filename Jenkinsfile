pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'this is build stage'
        build 'a'
      }
    }

    stage('test') {
      steps {
        echo 'this is testing'
        build 'b'
      }
    }

    stage('assigning a pipeline') {
      steps {
        build 'pipeline1'
      }
    }

  }
}