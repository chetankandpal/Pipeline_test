pipeline{
 agent any
  stages{
    stage('Clone Git'){
      steps{
       git 'https://github.com/chetankandpal/Pipeline_test.git'
      }
    }
    stage('Build Code'){
      steps{
       sh "chmod u+x Prog1.py"
       sh "./Prog1.py" 
      }
    
    }
    stage('Test Code'){
      steps{
       sh "chmod u+x Test.py"
       sh "./Test.py" 
      }
    
    }
    
    
    
  }
}
