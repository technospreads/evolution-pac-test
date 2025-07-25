pipeline {
agent any
  stages {
     stage ("This is my stage1"){
       steps {
          script {
		     a=40
			 b=30
			 if (a>=b){
			  println "Here is your A variable value is Big: ${a}"
			 }
			 else{
			   println "Here is your B variable value is Big: ${b}"			  
			 }
	            }
               }     
         }
     }
}
