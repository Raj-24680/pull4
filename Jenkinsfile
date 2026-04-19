pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                bat 'javac App.java'
            }
        }

        stage('Test') {
            steps {
                bat 'java App'
            }
        }

    }
}
