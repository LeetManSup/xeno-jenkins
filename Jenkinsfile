pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
		sh 'apt update && apt install g++'
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
