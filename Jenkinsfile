pipeline {
  agent any
  stages {
  steps {
    stage ('Build') {
      echo 'Running Build automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts : 'dist/tainSchedule.zip'
      }
    }
  }
  
}
