pipeline {
    agent any 
    stages {
        stage {
            steps ('Lintchecks') {
                sh "echo checking LintChecks"
                sh "~/node_modules/jslint/bin/jslint.js server.js"
                sh "lint checks completed!"
        }
    }
}