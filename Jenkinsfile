pipeline {
	agent 'any'
	stages {
		stage("working with variables") {
			steps {
				script {
						var1=20
						println "my var1 value is ${var1}"
						println "==== Printing default jenkins variables ===="
						println "WORKSPACE is ${WORKSPACE}"
						println "BUILD_NUMBER is ${BUILD_NUMBER}"
				}
			}
		}
	}
	
}
