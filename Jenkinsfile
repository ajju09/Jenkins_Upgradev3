pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        println "Hi, this is Fran from LevelUp360"
                        println "We are Starting the Testing"
                  }
            }
            stage('Build') {
                  steps {
                        println "Building Sample Maven Project"
                  }
            }
            stage('Deploy') {
                  steps {
                        println "Deploying in Staging Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        println "Deploying in Production Area"
                  }
            }
      }
}