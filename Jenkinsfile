pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''touch newFile.txt
pwd
ls'''
      }
    }

    stage('Backend') {
      steps {
        sh 'echo Backend'
      }
    }

    stage('FrontEnd') {
      steps {
        sh 'echo FrontEnd'
      }
    }

    stage('Static Analysis') {
      steps {
        sh 'echo Static'
      }
    }

    stage('Deployment') {
      steps {
        sh 'echo deploy'
      }
    }

  }
}