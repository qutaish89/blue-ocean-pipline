pipeline {
  agent any
  stages {
    stage('get tfs') {
      steps {
        echo 'first stage '
        powershell 'Set-Alias tf "C:\\Program Files (x86)\\Microsoft Visual Studio 9.0\\Common7\\IDE\\tf.exe"'
      }
    }

    stage('process') {
      steps {
        echo 'process'
      }
    }

  }
}