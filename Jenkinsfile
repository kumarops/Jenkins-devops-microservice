pipeline {
	agent any
	stages {
		stage ('Build') {
			steps {
              echo "Build"
			}
		}
		stage ('Test') {
			steps {
              echo "Test"
			}
		}
		stage ('Integration Test') {
			steps {
              echo "ntegration Test"
			}
		}		
	}	
	post {
		always {
			echo "always execute this"
		}
		success {
			echo "execute this when build success"
		}
		failure {
			echo "execute this when build faile"
		}
		//unchanged  //unstable
	}
}
