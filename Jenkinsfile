pipeline{
	agent { label 'slave-2'}
	stages{
        stage('Build stage') {
            steps {
                echo 'This is a build stage vivekadded for webhook1'
				sh 'sleep 5'
			}
		}
        stage('Push stage') {
            steps {
                echo 'This is push stage'
                sh 'sleep 5'
			}
		}
        stage('Deploy stage') {
            steps {
                echo 'This is deploy stage'
                sh 'sleep 5'
			}
		}
	}
}	
