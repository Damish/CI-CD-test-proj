pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Build the Maven project
                sh 'mvn -version'
                sh 'mvn clean package'
            }
        }
    }
}

