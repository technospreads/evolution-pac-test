pipeline {
    agent any
    stages {
        stage("This is my stage1") {
            steps {
                script {
                 
                    for (int i = 1; i <= 20; i++) {
                        println "Here is your variable I value: ${i}"
                    }
                }
            }
        }
    }
}
