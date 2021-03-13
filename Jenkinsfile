pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        sh 'echo "This is the build number $BUILD_NUMBER of $DEMO"'
      }
    }

  }
  environment {
    DEMO = '2021'
  }
}