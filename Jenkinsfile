pipeline {
  agent any
  stages {
    stage('first') {
      agent { label 'Slave-1-VMware' }
      steps {
        sh 'echo "Hi there"'
      }
    }

  }
}
