pipeline {
    agent any
    stages {
        stage("Build") {
            steps {
                sh "bundle install"
            }
        }
        stage("Testes") {
            steps {
                sh "echo 'simulando uma build'"
            }
        }
    
    }
}