pipeline {
  agent any
  stages {
    stage('') {
      steps {
        withKubeCredentials() {
          sh 'kubect get pod -n cale'
        }

      }
    }

  }
}