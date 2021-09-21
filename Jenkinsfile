pipeline {
  agent any
  stages {
    stage('dev stage') {
      steps {
        build 'a'
      }
    }

    stage('testing stage') {
      steps {
        echo 'this stage is executed succefully.'
        build 'b'
      }
    }

  }
}