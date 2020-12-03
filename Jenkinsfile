pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'Build stage'
          }
        }

        stage('Test') {
          steps {
            echo 'Test stage'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'Deploy Stage'
      }
    }

  }
}