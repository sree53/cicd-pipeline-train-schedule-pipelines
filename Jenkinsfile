pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        echo 'Running my Build Automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
       }
     }
    } 
