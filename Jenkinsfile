pipeline {
  agent any
  environment {
		registryCredential = 'dockerhub' 
	}
  stages {
    stage('Build') {
			steps {
				{
					sh 'docker build -t bilalahmed55/backend-python-app .'
				}
			} 
		}
  }
}