pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'my first demo '
        sh 'echo "hi this my $BUILD_NUMBER build"'
      }
    }

  }
  environment {
    Demo = '1'
  }
}