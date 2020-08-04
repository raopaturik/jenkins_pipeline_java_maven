pipeline {
    agent any
    tools {
        maven 'Maven' 
    }
    stages {
        stage('Example') {
            steps {
               bat 'mvn --version'
               bat 'mvn clean'
                
            }
        }
    }
}
