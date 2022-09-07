pipeline {
  agent any
  stages {
    stage('Run Build') {
      steps {
        sh './mvnw package'
      }
    }
    stage('Run Tests') {
      steps {
        sh './mvnw test '
      }
    }
  }
}
