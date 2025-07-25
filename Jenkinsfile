pipeline {
agent any
  stages {
     stage ("This is my stage1"){
       steps {
          script {
             a=1
			 while (a<=10){
			   println "Here is your variable A value: ${a}"
			a=a+1 
		}
             }
          }     
        }
     }
 }
