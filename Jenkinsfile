pipeline {
    agent any
    
    tools {
        gradle 'Gradle-6.2'
    }
    stages {
         stage("run forntend") {
              steps {
                  echo 'executing yarn...'
                  nodejs('Node-12.0.0') {
                       sh 'yarn install'
                       }
                   }
           }
           stage("run backend") {
               steps {
                   echo 'executing gradle...'
                    sh './gradlew -v'
                    
                }
           }
     }
}
