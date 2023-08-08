pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git url: 'https://github.com/nareshh49/javapl-2506.git'
                sh 'ls -lart'
                sh 'javac hello.java'
            }
        }
        stage('Run') {
            steps {
                sh 'ls -lsrt'
                sh 'java Hworld'
            }
        }
    }
}
