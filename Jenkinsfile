pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                script {
                    // Clean and build the project using Maven
                    sh './mvnw clean install'
                }
            }
        }
        stage('Test') { 
            steps {
                script {
                    // Run tests using Maven
                    sh './mvnw test'
                }
            }
        }
        stage('Deploy') { 
            steps {
                script {
                    // This is a placeholder for deployment steps
                    echo 'Deploying application...'
                }
            }
        }
    }
}
