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
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Deploy to Dev'
      }
    }
    stage('Test') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Deploy to Test'
      }
    }
    stage('Prod') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Deploy to Prod'
      }
    }
  }
}