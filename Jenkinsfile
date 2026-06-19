pipeline {
    agent { label 'agent-1' }
    tools{
        maven 'Maven'
    }

    stages {
       
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
