pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        ansiColor(colorMapName: 'HTML')
      }
    }
    stage('stage2') {
      steps {
        load 'https://github.com/sonus0927/http/'
      }
    }
  }
  environment {
    prod = 'true'
  }
}