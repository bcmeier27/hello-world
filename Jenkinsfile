pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'First stage'
      }
    }
    stage('stage2') {
      steps {
        parallel(
          "stage2": {
            build 'test1'
            
          },
          "stage2b": {
            echo 'building test'
            
          }
        )
      }
    }
    stage('') {
      steps {
        echo 'Finished!'
      }
    }
  }
}