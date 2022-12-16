
pipeline{

agent any

stages{


stage('clone the from git') {

steps {


  echo "cloning the code from github repo"

      }


}


stage('Build ') {

steps {

echo " Building the java code using maven"

       }






    }

stage('Test') {

steps {


echo "Testing the code"


}

  stage('code quality anaylsis') {
  
  
    steps {
    
    echo "performing code quality analysis (sonar)"
    
    }
  
  }



}


stage('Deploy') {

steps {

echo "Deploying the code"

}





   }


}



       }
