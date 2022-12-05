pipeline{
  agent any
  stages{
    stage("Git Checkout"){
      steps{

            git 'https://github.com/abharmantri/calculator.git'
      }
    }
    
    stage('Compile-package'){
      
      steps{
      
     bat 'mvn package'
      
      }
    
    }
  }
}
