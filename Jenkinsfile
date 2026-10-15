pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo '🛠️ Build projet Java en cours...'
                sh 'mvn clean compile'
            }
        }
        stage('Test') {
            steps {
                echo '✅ Tests unitaires Java...'
                sh 'mvn test'
            }
        }
    }
}