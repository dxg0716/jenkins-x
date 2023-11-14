pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'jenkins pipeline'
            sh 'ls'
          }
        }

        stage('build2') {
          steps {
            echo 'jenkins-pipeline-2'
          }
        }

      }
    }

  }
  environment {
    image = 'nginx'
  }
}