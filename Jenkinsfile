pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
		sh 'sudo apt update && sudo apt install g++'
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
