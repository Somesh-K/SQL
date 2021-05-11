pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        bat 'E:\\batchfiles\\dev_shore.bat'
      }
    }

    stage('staging Deploy') {
      steps {
        bat 'E:\\batchfiles\\dev_shore2.bat'
      }
    }

  }
}