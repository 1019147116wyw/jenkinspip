pipeline {
  agent any
  stages {
    stage('de') {
      steps {
        withKubeConfig(credentialsId: '111', serverUrl: 'https://111') {
          sh 'echo "a"'
        }

      }
    }

  }
}