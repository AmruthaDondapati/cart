@library('robot-shared-library') _

pipeline {
    agent any 
    stages {
        stage ('Lintchecks') {
            steps {
                script {
                    lintChecks()
                }
                // sh "echo Lintcheks needs to be done"
                // sh "echo Lintchceks were completed"
            }
        }
    }
}
