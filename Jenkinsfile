pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'this is build stage'
            build 'a'
          }
        }

        stage('testing stage') {
          steps {
            echo 'msg'
            build 'a'
          }
        }

        stage('deployment') {
          steps {
            emailext(subject: 'sample', body: 'body', from: 'venkataramanaramigani7890@gmail.com', replyTo: 'anikumabuddalli@gmail.com', to: 'anilkumarbuddalli@gmail.com')
          }
        }

      }
    }

  }
}