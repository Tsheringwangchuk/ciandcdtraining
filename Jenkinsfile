pipeline {
    agent any

    stages {

        stage('System Info') {
            steps {
                sh 'hostname'
                sh 'uptime'
                sh 'df -h'
            }
        }

        stage('List Files') {
            steps {
                sh 'ls -lrt'
            }
        }
    }
}
