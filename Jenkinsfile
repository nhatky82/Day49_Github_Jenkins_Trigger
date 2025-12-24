pipeline {
    agent any
    
    stages {
       stage('Auto Trigger Test') {
          steps {
            sh 'chmod +x ky.sh'
            sh './ky.sh'
          }
         steps {
            sh 'chmod +x nhatky.sh'
            sh './nhatky.sh'
        }
      }
    }
}
