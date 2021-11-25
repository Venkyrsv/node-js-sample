pipeline {
    agent any 
    stages {
        stage('checkout') { 
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'Git', url: 'https://github.com/Venkyrsv/node-js-sample.git']]])
            }
        }
    }
}