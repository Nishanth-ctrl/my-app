pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "/usr/local/src/apache-maven clean"
            }
        }
        stage('--test--') {
            steps {
                sh "/usr/local/src/apache-maven test"
            }
        }
        stage('--package--') {
            steps {
                sh "/usr/local/src/apache-maven package"
            }
        }
    }
}
