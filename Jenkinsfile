def myfuc(int a, int b){
println "Here is your Adition of two arguments argumanet ${a},argument${b} is : " ${a+b}

}

pipeline {
agent any
  stages {
     stage ("This is my stage1"){
       steps {
          script {
 			   myfuc(10, 20)
		       }
             }
          }     
        }
    }
