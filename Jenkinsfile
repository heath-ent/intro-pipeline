pipeline {
  agent none
  stages {
    stage('Publish Event') {
      steps {
        publishEvent simpleEvent('{bheath}intro-pipeline')
      }
    }
  }
}