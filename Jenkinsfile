pipeline{
    agent{
        label "workstation"
    }
    stages{
        stage('Lintchecks'){
            steps{
                echo "Starting style checks"
                sh "npm i jslint"
                sh "/home/centos/node_modules/jslint/bin/jslint.js server.js"
                echo "***** Style checks are completed *****"
            }
            
        }
        stage('Static Code Analysis') {
            steps{
                echo "Starting code analysis"
                echo "We will updte after code analysis"
            }
        }
    }
}   