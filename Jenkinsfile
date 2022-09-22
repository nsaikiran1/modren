pipeline {
  agent {
    node {
      label 'sai'
    }

  }
  stages {
    stage('Jenkins') {
      parallel {
        stage('Jenkins') {
          steps {
            sh '''echo "Hai"
echo "Hello"'''
          }
        }

        stage('') {
          steps {
            echo 'hi'
          }
        }

      }
    }

  }
  environment {
    saikiran = '1'
  }
}