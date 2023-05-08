pipeline {
	agent any
  
  	tools {
    	maven 'skmns_maven_3.9.1'
	}
  
  	stages {
    	stage('Project Build') {
    		steps {
        		echo '=== start maven build ==='
            	sh 'mvn clean install'
            	echo '=== end maven build ==='
			}
    	}
  	}
}
