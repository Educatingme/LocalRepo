pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build Step 1') {
            steps {
                bat 'build.bat'
            }
        }

        stage('Build Step 2') {
            steps {
                bat 'build1.bat'
            }
        }

        stage('Build Step 3') {
            steps {
                bat 'build2.bat'
            }
        }
    }
}
