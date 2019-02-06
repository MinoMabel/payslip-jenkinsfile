pipeline {
    agent any 
    tools {
        maven 'LocalMaven' 
    }
    stages {
        stage('BUILD') {
            steps {
                build 'try-build'
            }
        }
        stage('TEST'){
            steps{
                build 'try-test'
            }
        }
        stage('DEPLOY'){
            steps{
                build 'try-deploy'
            }
        }
    }
}
        
