pipeline {
    agent any
   
    stages {
         stage("run forntend") {
              steps {
                  echo 'executing yarn...'
                  nodejs('Node-12.0.0') {
                       sh 'yarn install'
                       }
                   }
           }
           
     }
}
