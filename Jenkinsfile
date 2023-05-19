pipeline{
agent any
  environment{
    credin=credentials('userpass')
  }
  stages{
    stage("build"){
      steps{
      echo 'this is building stagedfgffg'
        echo "username is ${cedin_USR}"
        echo "password is ${credin_PSW}"
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
    post{
      fialure{
        mail to: 'kolluri.ashok@mindtree.com', subject: 'Pipe line Failed'
      }
    }
  
  }


}
