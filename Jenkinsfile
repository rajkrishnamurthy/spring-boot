pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh 'cat /var/jenkins_home/jobs/atmosphere/config.xml'
        echo '${$AO_HOST}'
      }
    }
  }
  environment {
    AO_HOST = 'https://gnextaodemo.apporbit.com'
    AO_USER_ID = 'admin@apporbit.com'
    AO_PASSWORD = 'admin1234'
  }
}