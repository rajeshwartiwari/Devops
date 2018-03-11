pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build started'
          }
        }
        stage('') {
          steps {
            readFile 'src/main/java/sample/logic/Calculator.java'
            readFile 'src/main/java/sample/logic/Calculator.java'
          }
        }
      }
    }
    stage('verify') {
      steps {
        echo 'Verify started'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }
    stage('End') {
      steps {
        echo 'End'
      }
    }
  }
}