pipeline {
     agent {
	   node {
	          label "built-in"
			 customWorkspace "/root/jenkins"
			  
			  }
			  }
			  
			  environment {
			                Name = "rajkumar"
					PROF = "Devops"
					BATCH = "batch-2"
			  }
							
				stages {
				    stage('name') {
					    steps {
						   echo "{$Name}"
						   
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
				}
			}
