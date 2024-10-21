pipeline{

  agent any
 stages{
   stage("stage-1"){
  steps{
  sh '''
  rm -rf *
  '''
  }
 } 
 stage("stage-2"){
 steps{
 sleep 10
 }
}
}
}
