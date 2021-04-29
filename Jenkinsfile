pipeline {
    agent {
        docker {
            image "ruby"
        }
    }
    stages {
        stage("Build") {
            steps{
                sh "bundle install"
            }   
        }
        stage("Test") {
            steps{
                sh "echo 'simulando um teste automatizado'"
            }
        }
    }
}