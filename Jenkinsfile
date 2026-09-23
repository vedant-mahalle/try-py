pipeline {
    agent {
        docker {
            image 'python:3.12'
        }
    }

    stages {
        stage('Run Python') {
            steps {
                sh 'python --version'
                sh 'python hello.py'
            }
        }
    }
}
