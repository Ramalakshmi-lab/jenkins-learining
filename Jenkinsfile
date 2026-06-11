pipeline {
    agent { label 'agent-2' }
    tools {
        git 'Git-Linux'
    }
    stages {
        stage('Build') {
            steps {
                echo 'hi this is build'
            }
        }
    }
}
