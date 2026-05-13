pipeline {
    agent any

    stages {

        stage('System Info') {
            steps {
                sh 'echo "=== System Information ==="'
                sh 'hostname'
                sh 'uptime'
                sh 'df - h'
                sh 'free - m'
            }
        }

        stage('List Files') {
            steps {
                sh 'echo "=== Current Directory ==="'
                sh 'ls - lrt'
            }
        }
    }
}

