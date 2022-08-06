node{
     
     def buildNumber = BUILD_NUMBER
     stage('SCM Checkout'){
        git url: 'https://github.com/prashanth19975/August_1.git',branch: 'master'
    }
    stage(" Maven Clean validate compile test Package"){
    }
     stage ("BuildDocker image"){
          sh "docker build -t prashanth19975/java-web-app:${buildNumber} ." 
    }      
}
