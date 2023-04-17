pipeline {
  agent any
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo '"testing"'
          }
        }

        stage('parallel') {
          steps {
            echo '"parallel running"'
          }
        }

      }
    }

    stage('Build') {
      steps {
        echo '"building"'
      }
    }

    stage('Clean UP') {
      steps {
        echo '"cleaning up"'
      }
    }

  }
}