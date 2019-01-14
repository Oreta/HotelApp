pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'mvn package'
      }
    }
    stage('Report') {
      steps {
        echo 'I TRY TO COMMUNICATE'
      }
    }
    stage('rep') {
      steps {
        sh './jenkins/scripts/deliver.sh'
      }
    }
  }
}