pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'code checkout'
            }
        }
         stage('Build') {
            steps {
    git 'https://github.com/Aniket10720/spring-boot-war-example.git'
            }
        }
      stage('Test') {
            steps {
                echo 'code test'
            }
        }
         stage('Deploy') {
            steps {
                echo 'code deploy'
            }
        } 
    }
}
