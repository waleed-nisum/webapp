pipeline {
  agent any
      stages {
          stage('Build') {
            steps {
              sh "${MAVEN_HOME}/bin/mvn clean package"
              }
         }
  }
  
}
