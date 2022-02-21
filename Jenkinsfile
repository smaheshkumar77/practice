pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Jenkins pipeline -Build"'
              }
        }
        stage('Test') {
		steps {
		   sh 'echo "Jenkins pipeline -Test"'
		}
        }
        stage('Deploy') {
		steps {
		   sh 'echo "Jenkins pipeline - Deploy"'
		}
        }
    }
}
