pipeline {
    agent any
    
    agent
    
    stages {
        stage('Checkout GIT'){
            steps {
                
                echo 'pulling...';
                git branch : 'master',
                url : 'https://github.com/Styvekamga/SpringAop.git';
                
            }
        }
        
        stage('testing maven') {
            steps {
                sh """mvn -version"""
            }
        }
        
    }
}
