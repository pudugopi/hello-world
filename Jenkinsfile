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
         echo "Buil the project"
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
