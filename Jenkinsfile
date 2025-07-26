pipeline {
agent any
  stages {
     stage ("This is my stage1"){
       steps {
          script {

		  File obj1 = new File("/tmp/ravi.txt")
                  //obj1.write("Hi Team welcome to Groovy file operation")
		  println "Here is your file data ${obj1.text}"
		  for (line in obj1.readlines()){
			  println "Here is your line data---- ${line}"
		  }
		}
             }
          }     
        }
    }
