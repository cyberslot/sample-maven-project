pipeline {
    agent any
    stages {
    stage('maven install') {
      steps {
        withMaven(jdk: 'jdk', maven: 'maven') {
          sh 'mvn clean install'
        }
      }
    }
  }  
}
