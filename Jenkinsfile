pipeline {
  agent any //run on any available jenkins agent
  
  stages{
  
    stage("build"){
      steps {
        echo 'building the application...'
        javac HelloWorld.java
      }
    }
    
    stage("test"){
      steps {
        echo 'testing the application...'
      }
    }   
    
    stage("deploy"){
      steps {
        echo 'deploying the application...'
      }
    }
    
    
  }
}
