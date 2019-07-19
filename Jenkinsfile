pipeline {
  agent any
  stages {
    stage('Build and test') {
      parallel {
        stage('Build and test') {
          agent any
          steps {
            echo 'starting process'
            input 'Enter the branch id'
          }
        }
        stage('Stage1') {
          steps {
            sh 'echo "hello world"'
          }
        }
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
  environment {
    label = 'host'
  }
}