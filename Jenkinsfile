@Library('my-shared-libraries') _

pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
            gitCheckout(
                branch: "main",
                url: "https://github.com/hyarelgits/hyarel_java_app.git"
            )
            }
        }
        stage('mvn test'){

            steps{
               script{

                   mvnTest()

               }
            }

        }
       
    }
}
