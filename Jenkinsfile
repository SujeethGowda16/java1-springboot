pipeline {
    agent any

    stages {
        stage('Build'){
            steps{
                echo 'build'
                sh 'mvn clean packages'
            }
        }
        stage('Test'){
            steps{
                echo 'Test'
                sh 'mvn test'
            }
        }
        stage('Quality Gate - Sonar Qube'){
            steps{
                echo 'SonarQube'
            }
        }

        //CD
        stage('Deploy to Dev'){
            steps{
                echo 'Deploy to Dev'
            }
        }          
        stage('Deploy to Staging'){
            steps{
                echo 'Deploy to staging'                
            }
        }        
        stage('Deploy to Prod'){
            steps{
                echo 'Deploy to prod'
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
