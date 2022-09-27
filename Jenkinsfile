pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh 'echo "This is demo $DEMO_NUMBER for demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}