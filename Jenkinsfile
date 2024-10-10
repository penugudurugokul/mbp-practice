pipeline{
  agent any
  stages{
    stage("code checkout"){
      when{
        branch "develop"
      }
      steps{
        echo "Git checkout successful"
      }
    }
    stage("maven build"){
      when{
        branch "test"
      }
      steps{
        echo "Maven build successful"
      }
    }
    stage("Tomcat Deployment"){
      when{
        branch "main"
      }
      steps{
        echo "Tomcat deployment successful "
      }
    }
  }
}