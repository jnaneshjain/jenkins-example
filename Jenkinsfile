pipeline {
    agent any
    stages {
       stage ('Maven Build') {
                   steps {
                       sh 'mvn clean install -Dmaven.test.skip=true'
                   }
               }
    }
}