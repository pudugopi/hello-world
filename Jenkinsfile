pipeline{
    agent any
    stages{
      stage('source code from Github'){
        steps{
         echo 'clone source code from github'
        }
      }
      stage('Build'){
        steps{
         echo 'Build java project'
        }
      }
      stage('Test'){
        steps{
          echo"Testing source code"
        }
      }
      stage('Deploy'){
        steps{
          echo"Deploying ......"
        }
      }
    }
}
