pipeline {
    agent any
    stages {
        stage("This is my stage1") {
            steps {
                script {
                 list=[10,20,30,40,50]
                    for (i in ${list}) {
                        println "Here is your variable I value: ${i}"
                    }
                }
            }
        }
    }
}
