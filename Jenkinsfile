pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''
pipeline {
    agent { docker \'node:6.3\' }
    stages {
        stage(\'build\') {
            steps {
                sh \'npm --version\'
            }
        }
    }
}
'''
      }
    }
  }
}