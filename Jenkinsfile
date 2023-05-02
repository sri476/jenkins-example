pipeline {
    agent any
    tools {
        maven 'apache-maven-1.0.1' 
    }
    stages {
        stage('Example') {
            steps {
                sh 'mvn compile'
            }
        }
    }
}
