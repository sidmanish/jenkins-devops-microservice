pipeline{
	agent { docker { image 'maven:3.6.3'} }
	stages{
		stage("build"){
			steps{
				sh 'mvn --version'
				echo "Build"
				
			}
		}
		stage("Test"){
			steps{
				
				echo "Test"
				
			}
		}
		stage("IntegartionTest"){
			steps{

				echo "Integration Test"
			}
		}
	}
}
