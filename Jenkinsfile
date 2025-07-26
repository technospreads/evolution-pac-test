def myfuc(int a=1, int b=20){
println "Here is your Adition of two arguments argumanet a=${a},argument b=${b} is :  ${a+b}"

}

pipeline {
agent any
  stages {
     stage ("This is my stage1"){
       steps {
          script {
 			   myfuc(20)
		       }
             }
          }     
        }
    }
