pipeline{
    agent any
    
    stages{
       
       stage('Pull code from git'){
           
           steps{
                git url: 'https://github.com/buraashok/ashok-1.git'
               
                ///checkout([$class: 'GitSCM', branches: [[name: '']], 
                ///doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '', 
                
                
                //url: 'https://github.com/martinlindhe/wmi_exporter']]])
               
               /// url: 'https://github.com/buraashok/ashok-1']]])
                
                echo "All branches"
           }
       }
       
       stage('Running Script'){
           
           steps{
               sh "echo Inside gh-pages branch"
           }
       }
       
        
    }
}
