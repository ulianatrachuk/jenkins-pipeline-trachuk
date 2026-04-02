pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building project...'
                bat 'echo Build stage'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo Tests passed!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy stage'
                bat 'echo Deploy done'
            }
        }
    }
}