pipeline{
   agent any
     triggers {
       githubpush()
   }
   stages{
      stage('PrintMessage') {
         steps{
            echo "Hello, from multibranch" 
     }
    }
  }
}
