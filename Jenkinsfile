pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{
                    
                    git branch: 'master', url: 'https://github.com/hyarelgits/hyarel_java_app.git'
                }
            }
        }
    }
}
