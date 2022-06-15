pipeline {
   agent any
   stages {
       stage('Build') {
           steps {
               sh "./build.sh"
           }
       }
      stage('Deploy') {
          steps {
               sh """
               echo "Deploying Code"
               """
          }
      }
   }
}
