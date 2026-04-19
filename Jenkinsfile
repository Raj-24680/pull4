pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                bat 'javac App.java'
            }
        }
        stage('test'){
            steps{
                bat 'java App'
            }
        }
    }
}
