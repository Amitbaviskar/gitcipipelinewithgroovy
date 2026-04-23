pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Amitbaviskar/gitcipipelinewithgroovy.git'
            }
        }

        stage('Build') {
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
