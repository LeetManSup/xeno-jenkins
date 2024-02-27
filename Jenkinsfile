pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'g++ -o myapp main.cpp'
            }
        }
        stage('Test') {
            steps {
                sh './myapp'
            }
        }
    }
}
