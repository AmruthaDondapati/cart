@library('robot-shared-library')
pipeline {
    agent any 
    stages {
        stage ('Lintchecks') {
            steps {
                script {
                    lintChecks(cart)
                }
                // sh "echo Lintcheks needs to be done"
                // sh "echo Lintchceks were completed"
            }
        }
    }
}
