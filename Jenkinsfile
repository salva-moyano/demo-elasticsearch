pipeline {
  agent none
  options {
      buildDiscarder(logRotator(numToKeepStr: '100'))
  }
   stages {
        stage('Init') {
           script {
              println('Init step')
           }
        }
   }
   
   stage('Cleanup') {
      steps {
          script {
             println('Cleanup')
          }
      }
   }
}
