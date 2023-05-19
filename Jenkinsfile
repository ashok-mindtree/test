pipeline{
agent any
  environment{
    cred=credentials('userpass')
  }
  stages{
    stage("build"){
      steps{
      echo 'this is building stagedfgffg'
        echo "credentials are ${cred}"
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
