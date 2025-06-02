@Library('jenkins-shared-library') _
pipeline{
    agent {
        label 'ws'
    }
    stages{
        stage('lint checks'){
            steps{
                script{
                    hello.info1
                }
                
                sh "echo ***********Starting Style Checks****************"
                sh "npm install jslint"
                sh "/home/ec2-user/node_modules/jslint/bin/jslint.js server.js || true"
            }
        }    
        stage('Static Code Analysis'){
            steps{
                sh "echo ******** Starting Static Code Analysis *******"
                sh "echo welcome all to sonarcube"
            }
        }
    }
    
}
