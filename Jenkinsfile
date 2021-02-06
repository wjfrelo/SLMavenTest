pipeline {
	agent any
	tools {
    	maven 'MavenHome'
	}
	stages {
    	stage('Build') {
        	steps {
        	    sh "mvn compile"
        	}
    	}

    	stage("Unit test") {
        	steps {
            	sh "mvn test"
       	    }
    	}
    }
}
