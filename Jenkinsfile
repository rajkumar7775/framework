pipeline {
     agent {
	   node {
	          label "built-in"
			 customWorkspace "/root/jenkins"
			  
			  }
			  }
			  
			  environment {
			                NAME = "rajkumar"
					PROF = "Devops"
					BATCH = "batch-2"
			  }
							
				stages {
				    stage('name') {
					    steps {
						   echo "{$NAME}"
						   
						   }
						   }
				    
					stage('prof') {
					    steps {
						   echo "{$PROF}"
						   
						   }
						   }
						   
					stage('batch') {
					    steps {
						   echo "{$BATCH}"
						   
						   }
						}
				  }

				}
			
