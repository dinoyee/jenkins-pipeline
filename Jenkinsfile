pipeline {
  agent {
    node {
      label 'mac'
    }

  }
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build'
          }
        }

        stage('Test') {
          steps {
            echo 'Test'
          }
        }

      }
    }

    stage('Done') {
      steps {
        echo 'Done'
      }
    }

    stage('Done2') {
      steps {
        sh 'echo Dono2'
      }
    }

  }
}