pipeline{
    agent{
        label "node"
    }
    stages{
        stage("Lintchecks"){
            steps{
                sh "echo *** Lint check starting ***"
                sh "/home/centos/node_modules/jslint/bin/jslint.js server.js"
                sh "echo *** Lint check completed ***"
            }
            
        }
    }
    
}