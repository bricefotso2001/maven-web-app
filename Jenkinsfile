node('master')
  {
   def mavenHome = tool name: 'maven3.8.5'
  stage('1.git clone')
  {
  git credentialsId: 'bricefotso2001/****** (github_credentials)', url: 'https://github.com/bricefotso2001/maven-web-app.git'
  }
  stage('2mavenBuild')
  { 
    sh "${mavenHome}/bin/mvn clean package"
  }
  
  }
