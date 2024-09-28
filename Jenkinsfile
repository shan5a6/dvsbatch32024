pipeline {
  agent any 
  stages {
    stage('Working with loops') {
      steps {
        script {
          for(i=1;i<=5;i++) {
            println "my i value is ${i}"
          }

          j=1
          while ( j <= 5) {
            println "j value is ${j}"
            j = j + 1 
          }
          for (l in [10,20,30,40,50]) {
            print(l)
          }
          
        }
      }
    }
  }
}
