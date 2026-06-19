pipeline {
    agent { label 'agent-1' }
    
    stages {
       
        stage('Build') {
            steps {
                sh '''
                echo "\\033[32mSUCCESS: Build completed!\\033[0m"
                      echo "\\033[31mERROR: Something went wrong!\\033[0m"
                '''
            }
        }
    }
}
