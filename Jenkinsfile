def myfuc(int a=1, int b=20){
       result=a+b
	return result
}

pipeline {
agent any
  stages {
     stage ("This is my stage1"){
       steps {
          script {
 			    println "Here is your funtion return value   ${myfuc(20,4)}"
		            println "Here is your funtion return value  ${myfuc()}"
		            println "Here is your funtion return value  ${myfuc(2)}"
		       }
             }
          }     
        }
    }
