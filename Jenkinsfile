pipeline {
  agent any
  stages {
    stage('Build and test') {
      steps {
        fileExists 'p1.py'
        echo 'completing'
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