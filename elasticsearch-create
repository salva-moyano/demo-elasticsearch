
pipeline {
    agent none
    options {
        buildDiscarder(logRotator(numToKeepStr: '100'))
    }
    stages {
        stage('Init') {
            steps {
                script {
                    println('String')
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
}
