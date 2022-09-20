pipeline {
    agent { 
		docker { 
			image 'maven:3.8.4-openjdk-11-slim' 
			 args '-v /var/run/docker.sock:/var/run/docker.sock'
		} 
	}
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}