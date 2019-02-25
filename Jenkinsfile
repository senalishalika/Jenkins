node{
    stage('SCM Checkout'){
        
        git 'https://github.com/senalishalika/Jenkins'
    }
    stage('Initialize'){
        //def dockerHome = tool 'myDocker'
        def mavenHome  = tool 'myMaven'
        env.PATH = "${mavenHome}/bin:${env.PATH}"
        
    }
     stage('Build'){
         def mavenHome  = tool 'myMaven'
         echo "${mavenHome}/bin/mvn package"
    }
   
}
