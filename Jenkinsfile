pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'pwd'
                sh 'ls'
                
                sh 'git branch'
                sh 'git branch -r'
                
//                 sh 'touch hello.txt'
//                 sh 'echo "Hello World!" > hello.txt'
//                 sh 'cat hello.txt'
            }
        }
//         stage('Push') {
//             steps {
//                 withCredentials([string(credentialsId: 'github-token', variable: 'token')]) {
//                     sh 'curl -s -o /dev/null --show-error -H "Authorization: token $token" https://api.github.com/repos/andikabahari/jenkins-pipelines-test'
//                     sh 'git config --global user.email "andikabahari48@gmail.com"'
//                     sh 'git config --global user.name "Andika Bahari"'
//                     sh 'git add hello.txt'
//                     sh 'git commit -m "Create hello.txt"'
//                     sh 'git push origin main'
//                 }
//             }
//         }
//         post {
//             always {
//                 deleteDir()
//                 sh 'ls'
//             }
//         }
    }
}
