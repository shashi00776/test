pipeline {
	agent any  
	stages {
		stage('BUILD') {
			steps {
				sh '''
					 pwd
           ls
           git init
           git clone https://github.com/deesnest/pushtest.git
           ./test.sh
	   ls
	   pwd
	   '''
			}	
		}		
		 
	}
}
