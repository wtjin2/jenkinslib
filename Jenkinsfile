#!groovy

@Library('jenkinslib') _

def tools = new org.devops.tools()

String workspace = "/opt/jenkins/workspace"

//Pipeline
pipeline{

  agent any
  
  stages{
    stage("GetCode"){
      steps{
        script{
          tools.PrintMes("this is my lib!")
        }
      }
    }
  
  }

}
