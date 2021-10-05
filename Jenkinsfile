pipeline {
    agent any

    stages {
        stage('---clean---') {
            steps {
                Sh "mvn clean"
            }
        }
        stage('---test---') {
            steps {
                Sh "mvn test"
            }
        }
        stage('---package---') {
            steps {
                Sh "mvn package"
            }
        }
    }
}
