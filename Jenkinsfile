pipeline {
  agent any
  stages {
    stage('Example Stage') {
      parallel {
        stage('Example Stage') {
          steps {
            echo 'This will run automatically.'
          }
        }

        stage('') {
          steps {
            sh '111'
          }
        }

      }
    }

    stage('Deployment') {
      steps {
        echo 'Deployment will run after approval.'
      }
    }

  }
}