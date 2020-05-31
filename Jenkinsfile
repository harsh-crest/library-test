@Library("shared-library") _

pipeline {

    agent any
    stages {
		stage('Checkout') {
			steps {
				checkout scm
			}					
		}

		stage('Build') {
			steps {
				jenkinsJob.build()
			}					
		}
	}
}
