pipeline {
  agent any
  
  environment {
    DEMO='1.3'
  }
  
  stages {
    stage('Stage1') {
      steps {
        sh 'echo "This is demo $DEMO_NUMBER for demo $DEMO"'
        sh '''
        echo "Using a multiline shell step"
        chmod +x test.sh
        ./test.sh
        '''
      }
    }

  }
}
