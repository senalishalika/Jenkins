node{
    stage('SCM Checkout'){
        git 'https://github.com/senalishalika/Jenkins'
    }
    stage('Compile-Package'){
        sh 'mvn package'
    }
}
