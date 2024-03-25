pipeline {
    agent any
    tools{
        Maven 'maven'
    }

    stages {
        
        stage('validate') {
            steps {
               sh 'mvn validate'
            }
        }
        stage('complie') {
            steps {
               sh 'mvn compile'
            }
        }
        stage('test') {
            steps {
               sh 'mvn test'
            }
        }
        stage('package') {
            steps {
               sh 'mvn package'
            }
        }
    }
}
