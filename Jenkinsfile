pipeline {
    agent any

    stages {
        stage('---clean---') {
            steps {
                Sh "man clean"
            }
        }
        stage('---test---') {
            steps {
                Sh "man test"
            }
        }
        stage('---package---') {
            steps {
                Sh "man package"
            }
        }
    }
}
