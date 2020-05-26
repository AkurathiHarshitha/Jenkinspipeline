node {
   def mvnHome
   def branch     = "env.BRANCH_NAME".toString()
   def configpath = "./helm/charts/sparkpredict/config"
   stage('Preparation') { // for display purposes
      echo "1"
      sh "python --version"
   }
   stage('Build') {
      // Run the maven build
      echo "2"
      sh 'echo "$branch"'
      
      parallel(
      a: {
        echo "$branch"
      },
      b: {
        echo "This is branch b"
        echo "$branch"
      }
    )
   }
   stage('Results') {
      echo "3"
   }
   stage('Results') {
      echo "3"
   }
}
