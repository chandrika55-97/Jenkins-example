pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                 
                    sh "echo this is build"
            
            }
        }
        stage('Test') {
            steps {
                
                    sh "echo this is test"
                
            }
        }
        stage('Deploy') {
            steps {
                 
                    sh "echo this is deploy"
        
            }
        }
    }
    post{
        always{
            echo "this is run always"
        }
        success{
            echo " this is run when sucess"
        }
        failure{
            echo "this is run when pipeline is failure"
        }
    }
}