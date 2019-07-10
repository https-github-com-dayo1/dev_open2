pipeline {
  agent any
  stages {
    stage('say-hello2') {
      steps {
        sh '''pipeline {
  agent {
    label \'jdk9\'
  }
  stages {
    stage(\'\\\'Say Hallo!\\\'\') {
      steps {
        echo \'Hallo World!\'
        sh \'java -version\'
      }
    }
  }
}'''
        }
      }
    }
  }