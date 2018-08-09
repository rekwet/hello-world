pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh '''cd ~
cd /Users/louw/go/src/hello
go run hello.go'''
      }
    }
  }
}