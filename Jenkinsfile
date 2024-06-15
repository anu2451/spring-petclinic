
pipeline {
    agent any
   stages {
    stage('Maven Install') {
      agent {
       docker {
         image 'maven'
     }
  }
  steps {
       sh 'mvn clean install'
       }
     }
   }
 }
