node{
    stage('SCM Checkout'){
        
        git 'https://github.com/senalishalika/Jenkins'
    }
    stage('Compile-Package'){
        def mvnHome = tool name: 'maven_3_6_0', type: 'maven'
        echo "${mvnHome}/bin/mvn package"
    }
}
