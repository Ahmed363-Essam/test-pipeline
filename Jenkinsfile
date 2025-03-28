pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Message Completed'
      }
    }

    stage('Test Stage') {
      parallel {
        stage('Test Stage') {
          steps {
            echo 'test stage 2'
            echo 'Test Stage'
          }
        }

        stage('test 2') {
          steps {
            echo 'test another message'
          }
        }

      }
    }

    stage('Deploy Stage') {
      steps {
        echo 'Deploy Stage '
      }
    }

  }
}