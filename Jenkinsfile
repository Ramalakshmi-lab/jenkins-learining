
pipeline
{
    agent {label 'agent-2'}
    tools
    {
        maven 'Maven'
    }
    
    stages{
        stage('First')
        {
            steps
            {
                echo 'Nandu'
            }
        }
        stage('Build')
        {

            steps
            {
            sh 'mvn clean package'
            }
        }
            
    }
        
    
}
