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
                sh 'curl -i https://api.github.com/repos/andikabahari/jenkins-pipelines-test'
                
//                 withCredentials([string(credentialsId: 'github-token', variable: 'token')]) {
//                     sh 'echo "$token" > token.txt'
//                     sh 'cat token.txt'
//                 }
                
//                 sh 'git config --global user.email "andikabahari48@gmail.com"'
//                 sh 'git config --global user.name "Andika Bahari"'
//                 sh 'git add hello.txt'
//                 sh 'git commit -m "Create hello.txt"'
//                 sh 'git push origin main'
            }
        }
    }
}
