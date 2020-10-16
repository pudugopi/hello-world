pipeline{
    agent any
    stages{
      stage('source code from Github'){
        steps{
         git 'https://github.com/pudugopi/hello-world'
        }
      }
      stage('Build'){
        steps{
         sh 'clean install package'
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
