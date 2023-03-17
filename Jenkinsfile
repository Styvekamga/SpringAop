node {
        stage('Checkout GIT'){
                
                
           
                git : 'https://github.com/Styvekamga/SpringAop.git'
                
            }
        
        stage('Compile-Package') {
                
                def mvnHome = tool name: 'M2_HOME', type: 'maven'
                sh "${mvnHome}/bin/mvn package"
            }
}
