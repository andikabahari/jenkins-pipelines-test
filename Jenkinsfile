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
                withCredentials([string(credentialsId: 'github-token', variable: 'token')]) {
                    sh 'echo "$token"'
                }
                
//                 sh 'git config --global user.email "andikabahari48@gmail.com"'
//                 sh 'git config --global user.name "Andika Bahari"'
//                 sh 'git add hello.txt'
//                 sh 'git commit -m "Create hello.txt"'
//                 sh 'git push origin main'
            }
        }
    }
}
