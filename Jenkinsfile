pipeline {
    	agent any
    
  	tools {nodejs "node"}
	
	 stage('Build') {
            steps {
                echo 'Building..'
            }
        }
	stage('Build') {
		sh 'npm install'
	}
	stage('Test') {
		sh 'npm test'
	}
    
}
