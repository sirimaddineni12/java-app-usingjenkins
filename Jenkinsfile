pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/sirimaddineni12/java-app-usingjenkins.git'
            }
        }

        stage('Compile Java Code') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }

        stage('Run Java Program') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
