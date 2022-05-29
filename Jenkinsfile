node('master')
  {
   def mavenHome = tool name: 'maven3.8.5'
  stage('1.git clone')
  {
  git credentialsId: 'github_credentials', url: 'https://github.com/Fotso-Technologies/maven-web-app'
  }
  stage('2mavenBuild')
  { 
    sh "${mavenHome}/bin/mvn clean package"
  }
