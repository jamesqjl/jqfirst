pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "build"'
      }
    }

    stage('Test') {
      steps {
        echo 'run test'
      }
    }

    stage('deploy') {
      steps {
        echo 'deployed'
      }
    }

  }
}