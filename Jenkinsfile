pipeline {
	agent any

	stages {
		stage('Build') {
			steps {
				sh 'mvn -B -X -DskipTests clean package'
			}
		}
	}
}
