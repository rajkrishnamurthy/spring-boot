pipeline {
  agent any
  stages {
    stage('Print Message') {
      steps {
        echo 'Test Message ${params.AO_HOST}'
      }
    }
  }
  environment {
    AO_HOST = 'https://gnextaodemo.apporbit.com'
    AO_USER_ID = 'admin@apporbit.com'
    AO_PASSWORD = 'admin1234'
  }
}
