pipeline{
agent any
  environment{
    credin=credentials('userpass')
  }
  stages{
    stage("build"){
      steps{
      echo 'this is building stagedfgffg'
        echo "credentials are ${credin}"
        echo "credentials are ${credin_PSW}"
      }
    }
    stage("test"){
      steps{
      echo 'this is testing stage'
      }
    }
    stage("deploy"){
      steps{
      echo 'this is deploy stage'
      }
    }
  
  }


}
