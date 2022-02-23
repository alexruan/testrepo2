pipeline {
  agent any
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


