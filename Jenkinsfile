pipeline {
    agent any
    environment {
        DEPLOY_ENV = 'preprod'
    }
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo "Building for ${env.DEPLOY_ENV} environment"
                // Add pre-production-specific build steps here
            }
        }

