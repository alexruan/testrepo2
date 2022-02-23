pipeline {
  agent any
  stages {
     stage ('Build') {
        steps {
            sh 'echo "hello world"'            
        }
     }
     stage('BuildMore'){
         steps {
            sh '''
                     echo ' Multiline shell steps'
             '''
         }
        }
     }
  }


