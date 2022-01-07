pipeline {
	agent { label 'Slave1' }
	stages {
		stage('BUILD') {
			steps {
				sh 'echo this is build stage in pipeline job'
				sh 'sleep 5'
			}
								
				
		}	
		stage('DEPLOY') {
			steps {
				sh ''' 
					sleep 5
					du -h 
				   '''
			}
		}
		
		stage('TEST') {
			steps {
				sh ''' 
					sleep 5
					du -h 
				   '''  
			}
		}
	}
}
