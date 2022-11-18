pipeline {
  agent any
  stages {
    stage('Stage') {
      steps {
        echo 'This is my pipeline and $BUILD_NUMBER'
        sh 'echo "This is my build $BUILD_NUMBER of Demo $DEMO"'
      }
    }

  }
}