pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'stage1'
        echo 'Additional Message'
      }
    }
    stage('stage2') {
      steps {
        parallel(
          "stage2": {
            echo 'stage2'
            
          },
          "stage2B": {
            echo 'Stage2B'
            
          }
        )
      }
    }
  }
}