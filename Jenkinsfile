pipeline {
  agent any
  stages {
    stage('Fluffy Test') {
      agent any
      steps {
        bat 'echo %BUZZ_NAME%'
      }
    }

    stage('Fluffy Deploy') {
      parallel {
        stage('Fluffy Deploy') {
          agent any
          steps {
            echo 'Placeholder'
          }
        }

        stage('parallel 1') {
          steps {
            echo 'Parallel'
          }
        }

        stage('parallel 2') {
          steps {
            echo 'Parallel 2'
          }
        }

      }
    }

  }
  environment {
    BUZZ_NAME = 'Worker Bee'
  }
}