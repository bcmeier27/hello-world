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
        mail(subject: 'stage1 complete', body: 'Stage 1 of the Jenkins BlueOcean hello-world pipeline is complete.', from: 'berniemeier@gmail.com', to: 'berniemeier@gmail.com')
      }
    }
  }
}