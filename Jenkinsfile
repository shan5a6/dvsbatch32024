pipeline {
  agent any 
  stages {
    stage('Working with fileoperations') {
      steps {
        script {
          File file = new File("/tmp/mydata.txt")
          def file_content = file.readLines()
          println "Lines\n ${file_content}"
          for(line in file_content){
            println "${line}"
          }
        }
      }
    }
  }
}
