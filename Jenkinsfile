pipeline {
  agent none
  stages {
    stage('Build') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Hi Wed'
      }
    }
    stage('Dev') {
      agent any
      steps {
        echo 'Deploy to Dev'
      }
    }
    stage('Test') {
      agent any
      steps {
        echo 'Deploy to Test'
      }
    }
    stage('Prod') {
      agent any
      steps {
        echo 'Deploy to Prod'
      }
    }
  }
}