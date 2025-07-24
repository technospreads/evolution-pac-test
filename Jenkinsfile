pipeline {
agent any
environment {
  SUBJECT = "Jenkins-Pac"
  BATCHNO = "2"
}
parameters {
  choice choices: ['DEV', 'QA', 'SIT', 'PRE-PROD', 'PROD'], description: 'Please select your environment in which you are deploying', name: 'Please select your environment in which you are deploying'
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
		               println "Here is choosen environment :  ${params.env}"


		  
             }
          }     
        }
     }
 }
