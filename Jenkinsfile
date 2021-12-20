pipeline{
  agent any
  stages{
    stage('archiving artifacts'){
      steps{
         archiveArtifacts artifacts: 'output.txt', fingerprint: true
      }
    }
  }
}
