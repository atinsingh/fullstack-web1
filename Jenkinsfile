pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'sh \'mvn compile\''
      }
    }

  }
  environment {
    buildType = 'DevOps'
  }
}
