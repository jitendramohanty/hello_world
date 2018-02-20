pipeline {
  agent any
  stages {
    stage('Build and test') {
      agent any
      steps {
        echo 'starting process'
      }
    }
    stage('deploy') {
      steps {
        sleep 5
        echo 'Going to deploy'
        sleep 2
        echo 'Deployment completed'
      }
    }
  }
}