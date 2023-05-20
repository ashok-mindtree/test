pipeline{
agent any
  environment{
    credin=credentials('userpass')
  }
  stages{
    stage("build"){
      steps{
      echo 'this is building stagedfgffg'
        echo "username in stage-1 is ${credin_USR}"
        echo "password in stage-1 is ${credin_PSW}"
      }
    }
    stage("test"){
      steps{
      echo 'this is testing stage-2'
        
       
      }
    }
    stage("deploy"){
      steps{
      echo 'this is deploy stage'
      }
    }
    
  
  }
  post{
      failure{
        echo "Pipeline Failed"
      }
    }


}
