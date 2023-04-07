pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/prithvirajpowar/java.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
