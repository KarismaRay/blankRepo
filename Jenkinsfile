pipeline {
   agent any

   stages {
      stage('git clone') {
         steps {
            sh 'echo Downloading code'
         }
      }
      stage('git compile') {
         steps {
            sh 'echo compile code'
         }
      }
      stage('git approval') {
         steps {
            input 'echo Approval needed?'
         }
      }
      stage('git deploy') {
         steps {
            sh 'echo Deploy code'
         }
      }
}
}
