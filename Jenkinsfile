
pipeline{

agent any

stages{


stage('clone the from git') {

steps {


  echo "cloning the code from github repo"
  git branch: 'main', url: 'https://github.com/BecomeDevops/teamrepo.git'

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
  
}

  stage('code quality anaylsis') {
  
  
    steps {
    
    echo "performing code quality analysis (sonar)"
    
    }
  
  }






stage('Deploy') {

steps {

echo "Deploying the code"

}





   }


}



       }
