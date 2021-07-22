pipeline{

 angentany
  tools{
    maven apache manven
  }
  stages{
    stage('buildstage'){
      steps{
        echo 'hell maven'
        sh   'maven --version'
      }
     
    }
    stage('sonarstage'){
      steps{ 
        echo ' hello sonar qube'
        sh   ' sonar --version'
      
      }
    }
    
    stage('deploys in tonexus'){
      enivorment{
         name = hanumantharao
      }
      steps{
        echo 'hello nexus'
        sh  'nexus --version'
      
     }
   }
  
 }











}
