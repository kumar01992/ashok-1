pipeline{
    agent any
    
    stages{
       
       stage('Pull code from BitBucket'){
           
           steps{
               
                echo "All branches"
           }
       }
       
       stage('Running Script'){
           
           steps{
               sh "echo Inside gh-pages branch"
           }
       }
       
       stage('Deploy')
       {
       steps 
       {
       sh "echo Sonarqube"
       }
       }
    }
}
