Pipeline {
        agent any
        stages{
        stage("Checkout GIT"){
                steps{
                        git url: 'https://github.com/Styvekamga/SpringAop.git' 
                }
                               
            }        
        stage("Build-Code"){
                steps{
                        sh "mvn clean install"
                }
                               
            }        
        }
}
