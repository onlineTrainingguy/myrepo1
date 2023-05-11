pipeline {
  agent any
  stages {
    stage('PreprationStage') {
      parallel {
        stage('PreprationStage') {
          steps {
            echo 'Prepration Stage Step'
          }
        }

        stage('Prep-2 Stage') {
          steps {
            echo 'Prep-2 step'
          }
        }

      }
    }

    stage('Build') {
      steps {
        echo 'Build Step'
      }
    }

  }
}