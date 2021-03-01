pipeline {
    agent { label 'docker-agent' } 
    stages {
        stage('clone source-code') {
            steps {
                git 'https://github.com/gioanlevanluat/hello-jenkins.git'
            }
        }
    }
}
