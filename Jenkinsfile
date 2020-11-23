pipeline{
   agent any
     triggers {
       githubPush()
   }
   stages{
      stage('PrintMessage') {
         steps{
            echo "Hello, from multibranch" 
     }
    }
  }
}
