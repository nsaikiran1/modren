pipeline {
  agent any
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

    stage('error') {
      steps {
        echo 'Hi all'
      }
    }

  }
}