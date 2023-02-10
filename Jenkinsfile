pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{
                    
                    git branch: 'main', url: 'https://github.com/ramakrishna8254/demoappwithsonar.git'
                }
            }
            
            stage('UNIT testing'){
            
                steps{
                    sh 'mvn test'
                }
            }
        }
        }
    }
        
