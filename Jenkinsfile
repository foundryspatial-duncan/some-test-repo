pipeline {
  agent any
  stages {
    stage('do something') {
      steps {
        parallel(
          "do something": {
            echo 'hello world'
            
          },
          "": {
            sleep 5
            
          }
        )
      }
    }
    stage('print message') {
      steps {
        echo 'slept 5 seconds'
      }
    }
  }
}