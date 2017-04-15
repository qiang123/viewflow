pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        parallel(
          "build": {
            sh 'echo "Hello world!"'
            
          },
          "build1": {
            echo 'hello world1'
            
          }
        )
      }
    }
  }
}