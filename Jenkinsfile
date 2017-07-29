pipeline {
  agent any
  stages {
    stage('') {
      steps {
        echo 'Test Message'
        sh 'go Connect2AOHost {AO_HOST}'
      }
    }
  }
  environment {
    AO_HOST = 'https://gnextaodemo.apporbit.com'
    AO_USER_ID = 'admin@apporbit.com'
    AO_PASSWORD = 'admin1234'
  }
}