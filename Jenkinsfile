pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        sh 'mvn clean install'
        echo 'print mvn build over'
      }
    }
    stage('Test') {
      steps {
        sh 'clean install'
      }
    }
  }
}