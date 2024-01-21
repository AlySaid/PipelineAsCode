pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        timeout(time : 5, unit: 'SECONDS'){
          sh 'sleep 10'
        }
        echo 'Build Completed...'
      }
    }
   stage('Test') {
      steps {
        echo 'Testing Completed...'
      }
    }
  }
}