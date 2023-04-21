pipeline {
  agent any
  stages {
    stage('node1') {
      steps {
        echo 'node1 success'
      }
    }

    stage('node2') {
      steps {
        echo 'node2 success'
      }
    }

    stage('node3') {
      steps {
        echo 'node3 success'
      }
    }

    stage('Build') {
      steps {
        sh './mvnw clean compile'
      }
    }

  }
}