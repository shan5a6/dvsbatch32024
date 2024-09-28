def myfn() {
  println "welcome to jenkins functions"
}

def myoperation(a=500,b=50) {
  sum = a + b
  return(sum)
}

pipeline {
  agent any 
  stages {
    stage('Working with functions') {
      steps {
        script {
          myfn() // Calling myfn 
          myoperation()
          println myoperation(20,30)
        }
      }
    }
  }
}
