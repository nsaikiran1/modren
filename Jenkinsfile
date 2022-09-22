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

        stage('new') {
          steps {
            echo 'hi'
          }
        }

      }
    }

    stage('') {
      steps {
        echo 'Hi all'
      }
    }

  }
  environment {
    saikiran = '1'
  }
}