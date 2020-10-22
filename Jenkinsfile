pipeline {
  agent any
  stages {
    stage('Fluffy Test') {
      agent any
      steps {
        echo 'I am a ${BUZZ_NAME}'
      }
    }

    stage('Fluffy Deploy') {
      agent any
      steps {
        echo 'Placeholder'
      }
    }

  }
  environment {
    BUZZ_NAME = 'Worker Bee'
  }
}