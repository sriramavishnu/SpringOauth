
node {

    stage('git checkout'){
    
        git 'https://github.com/sriramavishnu/SpringOauth'
    }
    
    statge('Maven Build'){
        
        sh 'mvn clean install package'
    
    }
}
