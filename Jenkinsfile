node{
     
    stage('SCM Checkout'){
        git url: 'https://github.com/prashanth19975/August_1.git',branch: 'master'
    }
    stage(" Maven Clean Package"){
      def mavenHome =  tool name: "Maven-3.0.5", type: "maven"
      def mavenCMD = "${mavenHome}/bin/mvn"
      sh "${mavenCMD} clean package"
     }
       
}
