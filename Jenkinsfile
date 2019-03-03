pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
               echo 'This is buildingstage.'
                sh 'mvn clean install'
            }
        }
    }
}