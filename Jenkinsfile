library identifier: 'jenkins-pipeline-demo-library@master',
	retriever: modernSCM([$class: 'GitSCMSource', remote : 'https://github.com/chiranjivkumar/jenkins-pipeline-demo-library.git'])

pipeline {
	agent any {
	stages {
		stage('Audit tools') {
			steps {
			 ausitTools()
			}
		}
	}
	}
}
