pipeline {
    agent {label 'agent-1' }
    tools{

        maven 'Maven'
    }
    stages {
        stage('First') {
            steps {
                script {
                    echo 'hi this is rambo'
                }
                steps{
                    mvn install }
                
            }
        }
    }
}
