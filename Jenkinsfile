
pipeline {
    agent {label 'agent-1'}

    stages {
        stage('Build') {
            steps {
                ansiColor('xterm') {
                    sh '''
                      echo -e "\\033[32mSUCCESS: Build completed!\\033[0m"
                      echo -e "\\033[31mERROR: Something went wrong!\\033[0m"
                    '''
                }
            }
        }
    }
    post{
        always{
            deleteDir()
        }
    }
}

