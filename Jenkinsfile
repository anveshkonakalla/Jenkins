pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                bat "mvn.cmd clean"
            }
        }
        stage('--test--') {
            steps {
                bat "mvn test"
            }
        }
        stage('--package--') {
            steps {
                bat "mvn package"
            }
        }
    }
}
