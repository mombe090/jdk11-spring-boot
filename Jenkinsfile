pipeline {
  agent {
    node {
      label 'jenkins-slave'
    }

  }
  stages {
    stage('select') {
      agent {
        node {
          label 'jenkins-slave'
        }

      }
      steps {
        sh 'echo hello africa'
      }
    }

  }
}