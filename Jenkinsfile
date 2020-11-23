pipeline{
   agent any
     triggers {
       githubPush()
   }
   stages{
      stage('PrintMessage') {
         steps{
            echo "Hello, from multibranch"
            steps{
              echo "I am intentionally making this commit, to validate my githubPush trigger from this file"
            }
     }
    }
  }
}
