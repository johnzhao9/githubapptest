pipeline {
  agent any
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'hi'
          }
        }

        stage('parallel thing') {
          steps {
            echo 'sametime'
          }
        }

      }
    }

    stage('') {
      steps {
        echo 'fd'
      }
    }

  }
}