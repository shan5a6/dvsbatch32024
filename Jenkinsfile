def myfn() {
  println "welcome to jenkins functions"
}

pipeline {
  agent any 
  stages {
    stage('Working with functions') {
      steps {
        script {
          myfn() // Calling myfn 
        }
      }
    }
  }
}
