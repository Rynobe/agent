pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Rynobe/agent.git']]])
            }
        }
        stage('Kiírás') {
            steps {
                echo 'Hello ez egy teszt'
            }
        }
    }
}
