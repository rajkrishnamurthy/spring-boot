pipeline {
  agent none
  stages {
    stage('Stage1') {
      steps {
        sh 'cat /var/jenkins_home/jobs/atmosphere/config.xml'
      }
    }
  }
  environment {
    AO_HOST = 'https://gnextaodemo.apporbit.com'
    AO_USER_ID = 'admin@apporbit.com'
    AO_PASSWORD = 'admin1234'
  }
}
