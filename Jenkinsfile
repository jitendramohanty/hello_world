pipeline {
  agent any
  stages {
    stage('Build and test') {
      agent any
      steps {
        echo 'starting process'
        input "Enter the branch id"
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
