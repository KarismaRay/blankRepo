pipeline {
   agent any

   stages {
      stage('git clone') {
         steps {
            sh 'echo Downloading code'
         }
      }
   }
   stages {
      stage('git compile') {
         steps {
            sh 'echo compile code'
         }
      }
   }
   stages {
      stage('git deploy') {
         steps {
            sh 'echo Deploy code'
         }
      }
   }
}
