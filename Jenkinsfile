pipeline {
agent any
  stages {
     stage ("This is my stage1"){
       steps {
          script {

		  File obj1 = new File("/tmp/ravi.txt")
                  //obj1.write("Hi Team welcome to Groovy file operation")
		  println "Here is your file data ${obj1.text}"
		  obj1.append("This is final discussion about file operation")
		  for (line in obj1.readLines()){
			  println "Here is your line data---- ${line}"
		  }
		}
             }
          }     
        }
    }
