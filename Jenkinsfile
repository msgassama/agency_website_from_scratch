pipeline {
  agent any
  stages {
    stage('stage-1') {
      parallel {
        stage('stage-1') {
          steps {
            echo 'Hello world'
            sleep 10
          }
        }

        stage('stage-2') {
          steps {
            echo 'Bye Bye'
          }
        }

      }
    }

  }
}