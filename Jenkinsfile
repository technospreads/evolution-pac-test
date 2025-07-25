pipeline {
    agent any
    stages {
        stage("This is my stage1") {
            steps {
                script {
                 
                    for (i in [10,20,30,40,50]) {
                        println "Here is your variable I value: ${i}"
                    }
                }
            }
        }
    }
}
