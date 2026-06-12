pipeline {
    agent { label 'ec2-agent' }

    tools {
        git 'Git-Linux'
        maven 'Maven-3'
    }

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build with Maven') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t myapp:latest .'
            }
        }
        stage('Run Container') {
            steps {
                sh 'docker run --rm -p 8080:8080 myapp:latest'
            }
        }
    }
}
