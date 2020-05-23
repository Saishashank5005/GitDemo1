pipeline {
      agent any 
      stages{
          stage('deploy-dev') {
             steps {
                echo 'hello'           
             }
          }
          stage('deploy-qa') {
             steps {
                echo 'qa'
                  input "Does the staging environment look ok?"
             }
          }
          stage('deploy-production') {
             steps {
                echo 'production'
             }
          }
      }
}
