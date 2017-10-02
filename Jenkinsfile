pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        parallel(
          "stage1": {
            echo 'First stage'
            
          },
          "test": {
            junit 'build/reports/**/*.xml'
            
          }
        )
      }
    }
    stage('stage2') {
      steps {
        parallel(
          "stage2": {
            sh 'echo Today\\\'s date is `date`'
            
          },
          "stage2b": {
            echo 'building test'
            
          }
        )
      }
    }
    stage('Finished') {
      steps {
        echo 'Finished!'
      }
    }
  }
}