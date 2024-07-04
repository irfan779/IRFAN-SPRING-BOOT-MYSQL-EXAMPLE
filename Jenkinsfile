pipeline {
    agent any

    tools {
        
        maven 'Maven'
    }

    stages {
        stage('Checkout') {
            steps {
                
                git 'https://github.com/irfan779/spring-boot-mysql-example.git'
            }
        }

        stage('Build') {
            steps {
                
                sh 'java --version'
                sh 'mvn clean install'
                sh 'mvn clean install -e'
            

        }
    }
    
}
}