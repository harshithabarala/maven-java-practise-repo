pipeline {
    agent any

    stages {
        stage('Clean') {
            steps {
                bat 'C:\\Users\\harsh\\apache-maven-3.9.16\\bin\\mvn.cmd clean'
            }
        }

        stage('Install') {
            steps {
                bat 'C:\\Users\\harsh\\apache-maven-3.9.16\\bin\\mvn.cmd install -DskipTests'
            }
        }

        stage('Test') {
            steps {
                bat 'C:\\Users\\harsh\\apache-maven-3.9.16\\bin\\mvn.cmd test'
            }
        }

        stage('Package') {
            steps {
                bat 'C:\\Users\\harsh\\apache-maven-3.9.16\\bin\\mvn.cmd package -DskipTests'
            }
        }
    }
}
