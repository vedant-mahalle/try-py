pipeline {
    agent any

    stages {
        stage('Run Python') {
            steps {
                sh 'python3 --version'
                sh 'python3 hello.py'
            }
        }
    }
}
