pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        echo '"This the build number $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '2021'
  }
}