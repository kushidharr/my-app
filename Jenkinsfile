pipeline {
  agent any
  stages {
    stage('list files') {
      steps {
        powershell(returnStdout: true, script: 'Get-ChldItem')
      }
    }
  }
}