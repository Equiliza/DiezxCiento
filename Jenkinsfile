pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                sh "mvn clean -e"
            }
        }

        stage('Compile') {
            steps {
                sh "mvn compile -e"
            }
        }

        stage('Test') {
            steps {
                sh "mvn test -e"
            }
        }
        
    }
}
