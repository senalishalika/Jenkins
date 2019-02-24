node{
    stage('SCM Checkout'){
        
        git 'https://github.com/senalishalika/Jenkins'
    }
    stage('Initialize'){
        def dockerHome = tool 'myDocker'
        def mavenHome  = tool 'myMaven'
        env.PATH = "${dockerHome}/bin:${mavenHome}/bin:${env.PATH}"
        
    }
     stage('Build'){
         def mavenHome  = tool 'myMaven'
         echo "${mvnHome}/bin/mvn package"
    }
   
}
