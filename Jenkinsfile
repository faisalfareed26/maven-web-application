pipeline 
{
  agent any
  stages 
   {
    stage('checkout code') 
     {
      steps 
       {
        git(url: 'https://github.com/faisalfareed26/maven-web-application.git', branch: 'developement', credentialsId: 'GitHub_Credentials', poll: true)
        }
      }
   }
 }
