pipeline {
  agent any
  stages {
    stage('hello1') {
      parallel {
        stage('hello1') {
          steps {
            sh 'echo \'hello\''
          }
        }
        stage('hello2') {
          steps {
            sh 'echo \'hello2\''
          }
        }
      }
    }
    stage('hello3') {
      parallel {
        stage('hello3') {
          steps {
            sh 'echo \'hello3\''
          }
        }
        stage('') {
          steps {
            echo 'hello'
          }
        }
      }
    }
  }
}