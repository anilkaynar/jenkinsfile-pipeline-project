pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}