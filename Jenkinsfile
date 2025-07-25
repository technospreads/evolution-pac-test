pipeline {
agent any
  stages {
     stage ("This is my stage1"){
       steps {
          script {
		     a= input message: 'Please enter a Variable A value', parameters: [string(defaultValue: '10', description: 'Variable 1 value', name: 'a')]
			 b=input message: 'Please enter a Variable B value', parameters: [string(defaultValue: '20', description: 'Variable 1 value', name: 'b')]
			 if (a.toInteger()>=b.toInteger()){
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
