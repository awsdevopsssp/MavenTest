node {
  stage ('Get SCM') {
     checkout scm
  }
  stage ('Clean the project') {
   sh 'mvn clean'  
  }
  stage ('Test') {
  sh 'mvn test'
  }
}
