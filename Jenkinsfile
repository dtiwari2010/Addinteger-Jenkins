node {
	stage('SCM Checkout') {
		git 'https://github.com/dtiwari2010/Addinteger-Jenkins.git'
		}
	stage('Comile-package') {
		sh 'mvn package'
		}
	stage("build & SonarQube analysis") {
                 sh 'mvn clean package sonar:sonar'
              }
          
	
}
