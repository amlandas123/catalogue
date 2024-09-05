pipeline{
    agent{
        label "node"
    }
    stages{
        stage("Lintchecks"){
            steps{
                sh "echo *** Lint check starting ***"
                sh "npm i jslint"
                sh "/home/centos/node_modules/jslint/bin/jslint.js server.js"
                sh "echo *** Lint check completed ***"
            }
            
        }
    }
    
}