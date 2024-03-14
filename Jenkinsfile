pipeline{
	agent any
	stages {
		stage('Build'){
			steps {
				echo "Build"
			}
		}
		stage('Test'){
			steps {
				echo "Test"
			}
		}
		stage('Integration Test'){
			steps {
				echo "Integration Test"
			}
		}
	} 
	post {
		always {
			echo "I am awwwwsoome! I'm running well."
		}
		success {
			echo "I run when successful."
		}
		failure {
			echo "I run when something fails."
		}
	}
}