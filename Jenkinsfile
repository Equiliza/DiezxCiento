pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                bat "mvn clean -e"
            }
        }

        stage('Compile') {
            steps {
                bat "mvn compile -e"
            }
        }

        stage('Test') {
            steps {
                bat "mvn test -e"
            }
        }
        
    }
}
