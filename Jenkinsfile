pipeline {
	agent 'any'
	parameters {
	  choice choices: ['dev', 'sit', 'uat', 'pt'], description: 'Choose the environment to deploy', name: 'ENV'
	  string defaultValue: '1.0.0', description: 'Provide the version number to deploy ', name: 'VERSION'
	}	
	stages {
		stage("working with variables") {
			steps {
				script {
						var1=20
						println "my var1 value is ${var1}"
						println "==== Printing default jenkins variables ===="
						println "WORKSPACE is ${WORKSPACE}"
						println "BUILD_NUMBER is ${BUILD_NUMBER}"
						println "==== Printing parameter variables ===="
						println "my ENV selected is ${ENV}"
						println "my VERSION selected is ${VERSION}"
				}
			}
		}
	}
	
}
