pipeline {
    agent any
    tools {
        maven "MAVEN"
        jdk "JDK"
    }
    stages {
      
        stage('Build') {
            steps {
                dir("/var/lib/jenkins/workspace/new pipeline1/my-app") {
                sh 'mvn -B -DskipTests clean package'
                }
            }
        }
     
   } 
}