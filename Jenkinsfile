@Library('robot-shared-library') _

pipeline {
    agent any 
    stages {
        stage ('LintChecks') {
            steps {
                script {
                    lintChecks("start","dev.com")
                }
                // sh "echo Lintcheks needs to be done"
                // sh "echo Lintchceks were completed"
            }
        }
    }
}
