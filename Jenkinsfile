pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Weekly Timetable'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing HTML file'
                bat 'if not exist index.html exit /b 1'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy stage completed'
            }
        }
    }
}