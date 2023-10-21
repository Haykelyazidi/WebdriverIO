pipeline {
    agent any
     tools {
        maven "mvn"
    }

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

    
        stage('Test') {
            steps {
                sh 'npx wdio'
            }
        }
    }
}
