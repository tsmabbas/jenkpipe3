pipleline {
  agent any
  stages  {
    stage('Build') {
      steps {
        sudo apt-get update
      }
    }
    stage('Test') {
      steps {
        mkdir example
      }
    }
    stage('Deploy') {
      steps {
        cd example
        pwd
      }
    }
  }
}
