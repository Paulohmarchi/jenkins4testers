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
                sh "bundle exec cucumber -p ci"
            }
        }
    }
}