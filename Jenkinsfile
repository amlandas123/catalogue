pipeline{
    agent{
        label "workstation"
    }
    stages{
        stage("Lintchecks"){
            steps{
                sh "echo ***Starting the style checks***"
                sh "/home/centos/node_modules/jslint/bin/jslint.js server.js"
                sh "echo ***Style checks are completed***"
            }

        
        }
        stage("Static Code Analysis"){
                sh "echo *** Starting code analysis ***"  
        }            
    }
}