pipeline {
  agent any 
  stages {
    stage('Working with fileoperations') {
      steps {
        script {
          File file = new File("/tmp/mydata.txt")
          def lines = file.readLines()
          println "Lines\n ${lines}"
          
        }
      }
    }
  }
}
