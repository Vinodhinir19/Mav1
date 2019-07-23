node{
	
stage('SCM Checkout'){
	 
   tool name: 'Maven1', type: 'maven'

            
	    git 'https://github.com/Vinodhinir19/Mav1.git'
	
	}
	
stage('Compile-Package')
{
	
		
sh "mvn package"		

	}
	
}
