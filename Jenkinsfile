pipeline {
  agent any
  stages {
    stage ('Stage one has begun'){
      steps {
        script {
          try{
            echo 'Everything is going to be okay'
            sh 'cat ./table_1.select.sql' 
          }
          catch(Exception e) {
            error "${e.message}"
          }
        }
      }
    }
  }

  def findimundi(String body, String subject) {
    echo 'bienbenido'
  }
}
