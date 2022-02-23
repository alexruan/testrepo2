pipeline {
  agent any
  tools {
     maven "MAVEN"
     jdk "JDK"
  }
  stages {
     stage ('Initialze') {
        steps {
            sh 'echo "hello world"'            
        }
     }
     stage('Build'){
         steps {
	    sh 'mvn -B -DskipTests clean package'
         }
        }
     }

  }


