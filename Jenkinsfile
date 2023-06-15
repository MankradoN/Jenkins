pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               sudo sh "./build.sh"
            }
        }
        stage('Test') {
            steps {
              sudo sh "./test.sh"
            }
        }
        stage('Deploy') {
            steps {
               sudo sh "./deploy.sh"
            }
        }
    }
}
