pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo 'Test Message {AO_HOST}'
      }
    }
  }
  environment {
    AO_HOST = 'https://gnextaodemo.apporbit.com'
    AO_USER_ID = 'admin@apporbit.com'
    AO_PASSWORD = 'admin1234'
  }
}