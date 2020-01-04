pipeline {
  agent {
    dockerfile {
      filename 'dockerfile'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'docker build -t rafaelptr/devops2019'
      }
    }

  }
}