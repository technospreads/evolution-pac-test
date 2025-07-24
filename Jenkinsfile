pipeline {
agent any
environment {
  SUBJECT = "Jenkins-Pa"
  BATCHNO = "2"
}
  stages {
     stage ("This is my stage1"){
       steps {
          script {
		     var1=20
            		      echo "Hellow welcome to Jenkins-PAC"
			      println "Here is your variable defineds:  ${var1}"
		               println "Here is your global variable :  ${env.BUILD_ID},${env.BUILD_URL}, "
		               println "Here is your global variable :  ${currentBuild.currentResult}, ${currentBuild.id}"
		               println "Here is your environment variable :  ${env.SUBJECT},  ${env.BATCHNO}"

		  
             }
          }     
        }
     }
 }
