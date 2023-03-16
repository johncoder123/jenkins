pipeline {
    agent any
    tools {
        maven 'Maven 3.5.0'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package spring-boot:repackage'
                sh 'printenv'

            }
        }
    }
}