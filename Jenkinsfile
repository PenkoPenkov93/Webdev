pipeline{
  agent any 
  
  stages{
    stage("Build"){
      steps{
       echo "Hello"
    
    
    
      }}
    stage ("Test"){
      steps{
       echo "World"
      }  }
    stage ("Publish"){
      steps{
       echo "From the git"
      }  }
 }
  post{
    always{
        echo"shutdown machine"
    }
    success{
      echo "congratulations"
    }
    failure{
      echo "send email for failure"
    }
    
  }
} 
