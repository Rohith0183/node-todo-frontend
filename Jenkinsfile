pipeline {
    	agent any
    
  	tools {nodejs "node"}
	
	 stage('Build') {
            steps {
                echo 'Building..'
            }
        }
	stage('Build NodeJs') {
		sh 'npm install'
	}
	stage('Test') {
		sh 'npm test'
	}
    
}
