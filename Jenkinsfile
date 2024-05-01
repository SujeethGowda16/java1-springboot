pipelines {
    agent any

    stages {
        stage('Build'){
            steps{

            }
        }
        stage('Test'){
            steps{
                
            }
        }
        stage('Quality Gate - Sonar Qube'){
            steps{
                
            }
        }

        #CD
        stage('Deploy to Dev'){
            steps{
                
            }
        }
        stage('Deploy to QA'){
            steps{
                
            }
        }
        stage('Deploy to UAT'){
            steps{
                
            }
        }
        stage('Deploy to Staging'){
            steps{
                
            }
        }        
        stage('Deploy to Prod'){
            steps{
                
            }
        }                        
    }
    post {
        failure{
            echo 'failed'
        }
        success{
            echo 'success'
        }
        aborted{
            echo 'aborted' 
        }
    }
}
