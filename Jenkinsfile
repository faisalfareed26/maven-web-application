pipeline {
  agent any
  stages {
    stage('Get Code from git') {
      steps {
        git(url: 'https://github.com/faisalfareed26/maven-web-application.git', branch: 'development', credentialsId: 'GitHub_Credentials', poll: true)
      }
    }

    stage('Build') {
      steps {
        sh 'mvn clean'
      }
    }

  }
}