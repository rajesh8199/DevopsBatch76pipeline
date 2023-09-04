pipeline {
  agent any
  stages {
    stage('plan') {
      steps {
        echo 'i  have a plan to  work on CICD'
      }
    }

    stage('code') {
      steps {
        echo 'i have a code  to work CICD'
      }
    }

    stage('Bilud') {
      parallel {
        stage('Bilud') {
          steps {
            echo 'i have a bilud  to  on work CICD'
          }
        }

        stage('test') {
          steps {
            echo 'i have a test  to  work on  CICD'
          }
        }

        stage('Release') {
          steps {
            echo 'i have Release  to work on CICD'
          }
        }

        stage('Deploy') {
          steps {
            echo 'i have a deploy  to work on CICD'
          }
        }

        stage('operate') {
          steps {
            echo 'i have a operate  to work on CICD'
          }
        }

      }
    }

  }
}