pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "Building now also in GitHub Actions..";ls -l /'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Testing..";ls -l /tmp'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying....";uname -a'
            }
        }
    }
}
