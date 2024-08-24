pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        nodejs('Node'){
          echo 'Build the NodeJS app'
          sh 'npm install'
        }
      }
    }
    }
}
