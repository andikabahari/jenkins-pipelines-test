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
        stage('Push') {
            steps {
                sh 'git add hello.txt'
                sh 'git commit -m "Create hello.txt"'
                sh 'git push'
            }
        }
    }
}
