pipeline {
  agent none
  stages {
    stage('Test') {
      steps {
        echo 'Coucou'
      }
    }
    stage('Test 2') {
      steps {
        echo 'Caca'
        timeout(time: 3)
      }
    }
  }
}