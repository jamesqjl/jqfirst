pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'checkout source code'
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