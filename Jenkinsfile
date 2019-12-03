pipeline{
    agent any  
	   stages{ 
	         stage(one){
			 steps {
			    echo 'Hi, This is Nazeer'
				 } 
				} 
			 stage(two){
                     steps {
		            input ('Do you want to proceed?')	
		             }
			 }
             stage(three){
                     When {
                	not { 
                                  branch "master"
                                 }
				}
                     steps { 
                          echo "hello"
			  }
						  
			}
		}				  
