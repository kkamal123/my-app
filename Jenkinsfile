pipeline {
    agent any
    tools { 
        maven 'Maven 3.8.2' 
        jdk 'jdk8' 
    }
    stages {
        stage('---clean---') {
            steps {
                sh "mvn clean"
            }
        }
        stage('---test---') {
            steps {
                sh "mvn test"
            }
        }
        stage('---package---') {
            steps {
                sh "mvn package"
            }
        }
    }
}
