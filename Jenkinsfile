pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'npm run start'
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