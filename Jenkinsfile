pipeline {
    agent any
    stages {


        stage('Checkout') {
            steps {
                git 'https://github.com/secret-moctar/Jenkins.git'
            }
        }
        stage('Compile') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java HelloWorld'
            }


        }

    }
}