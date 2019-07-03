node {
    Stage('SCM Checout'){
    git "https://github.com/Dhaamodharan/my-app"
    }
    Stage('Compile&Package'){
    //generate sntax using pipeline generator
    def mvnHome = too name: 'maven-3', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
    }
    
}
