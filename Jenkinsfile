pipeline {
  agent any
  stages {
    stage('Tool Version') {
      steps {
        sh '''java -version























 \\ git --version'''
      }
    }

    stage('Build process') {
      steps {
        sh './mvnw package'
      }
    }

  }
}