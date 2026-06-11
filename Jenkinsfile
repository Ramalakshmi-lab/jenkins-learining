pipeline {
    agent { label 'agent-2' }

    stages {
        stage('Build') {
            steps {
                echo 'hi this is build'
            }
        }

        stage('Test') {
            steps {
                echo 'hi this is test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'hi this is Deploy'
            }
        }
    }
}
