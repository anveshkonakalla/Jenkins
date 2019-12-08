pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                cmd "mvn clean"
            }
        }
        stage('--test--') {
            steps {
                cmd "mvn test"
            }
        }
        stage('--package--') {
            steps {
                cmd "mvn package"
            }
        }
    }
}
