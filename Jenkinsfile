pipeline {
    agent any
    stages {
        stage("This is my stage1") {
            steps {
                script {
                     for (i in 1..15) {
                        println "Here is your variable I value: ${i}"
                    }
                }
            }
        }
    }
}
