pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
	stage('NodeJs') {
	     steps {
		sh 'npm install'
	     }
	}
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('Release') {
            steps {
                echo 'Release into prod'
            }
        }
        stage('Prod') {
            steps {
                echo 'Release into prod'
                }
    }
    }
}
