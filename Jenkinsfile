pipeline {
  agent any
  stages {
    stage ('Stage one has begun'){
      steps {
        script {
          try{
            echo 'Everything is going to be okay'
          }
          catch(Exception e) {
            error "${e.message}"
          }
        }
      }
    }
  }
}
