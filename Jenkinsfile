node{
     
    stage('SCM Checkout'){
        git url: 'https://github.com/prashanth19975/August_1.git',branch: 'master'
    }
    stage(" Maven Clean Package"){
      def mavenHome = tool name: "Maven", type: "maven"
       sh "${mavenHome}/bin/mvn Clean Package"
     }
       
}
