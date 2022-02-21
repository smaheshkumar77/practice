pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Jenkins pipeline -Build"'
                sh 'ls -lta'
                sh 'mvn clean install'
              }
        }
        stage('Test') {
		steps {
		   sh 'echo "Jenkins pipeline -Test"'
		   sh 'hostname'
		}
        }
        stage('Deploy') {
		steps {
		   sh 'echo "Jenkins pipeline - Deploy"'
		   sh 'whoami'
		}
        }
    }
}
