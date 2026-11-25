pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Build') {
            steps {
                sh 'javac Main.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java Main'
            }
        }
    }
}
