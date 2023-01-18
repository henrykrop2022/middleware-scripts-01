 pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
                
                    sh 'middleware-scripts-01-${BUILD_NUMBER}.zip' * --exclude Jenkinsfile README.md
                
               
            }
        }
        
    }
}