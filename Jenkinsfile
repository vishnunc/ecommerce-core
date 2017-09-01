pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'building'
      }
    }
    stage('something') {
      steps {
        parallel(
          "something": {
            echo 'xyz'
            
          },
          "parallel": {
            echo 'parallel'
            
          }
        )
      }
    }
  }
}