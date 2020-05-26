node {
   def mvnHome
   def branch     = ${BRANCH_NAME}
   def configpath = "./helm/charts/sparkpredict/config"
   stage('Preparation') { // for display purposes
      echo "1"
      sh "python --version"
   }
   stage('Build') {
      // Run the maven build
      echo "2"
      sh 'echo "Hello World"'
      sh 'echo "Hello World"'
      sh '$configpath'
      
      parallel(
      a: {
        echo "This is branch a"
        echo "$branch"
      },
      b: {
        echo "This is branch b"
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
