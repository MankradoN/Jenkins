pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh "sudo ./build.sh"
            }
        }
        stage('Test') {
            steps {
               sh "sudo ./test.sh"
            }
        }
        stage('Deploy') {
            steps {
                sh "sudo ./deploy.sh"
            }
        }
    }
}
