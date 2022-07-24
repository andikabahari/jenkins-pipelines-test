pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'touch hello.txt'
                sh 'echo "Hello World!" > hello.txt'
                sh 'cat hello.txt'
            }
        }
    }
}
