pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        echo 'this is the compile job'
        sh 'npm compile'
      }
    }

    stage('test') {
      steps {
        echo 'this is the test job'
        sh 'npm test'
      }
    }

    stage('package') {
      steps {
        echo 'this is the package job'
        sh 'uptime'
      }
    }

  }
  tools {
    nodejs 'nodejs'
  }
  post {
    always {
      echo 'this is my dojo pipeline...'
    }

  }
}