pipeline {
    agent any


    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/akumar-gif/sample-java-programs.git'
            }
        }

        stage('Build') {
            steps {
                script {
                    // Set up any additional environment variables or configurations if needed
                    sh 'mvn clean install'
                }
            }
        }

    }

}
