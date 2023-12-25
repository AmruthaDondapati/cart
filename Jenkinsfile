pipeline {
    agent any 
    stages {
        stage {
            steps ('Lintchecks') {
                sh "echo checking LintChecks"
                sh "npm i jslint"
                sh "~/node_modules/jslint/bin/jslint.js server.js"
                sh "lint checks completed!"
            }
        }
    }
}
