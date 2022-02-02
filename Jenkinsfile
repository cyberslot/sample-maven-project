pipeline {
    agent any
    stages {
    stage('maven install') {
      steps {
        withMaven(globalMavenSettingsConfig: 'null', jdk: 'jdk', maven: 'maven', mavenSettingsConfig: 'null') {
          sh 'mvn clean install'
        }
      }
    }
  }  
}
