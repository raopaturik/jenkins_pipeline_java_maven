pipeline {
    agent any
    tools {
        maven 'Maven' 
    }
    stages {
        stage('Build') {
            steps {
               echo 'Build starting' 
               sh 'mvn --version'
               sh 'mvn clean'
               echo 'Build Completed'
                
            }
        }
    }
}
