pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Buildin ....'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Test...'
            }
        }
        
        stage('Sonar Analysis') {
            steps {
                echo 'sonar analysis...'
            }
        }
        
        stage('Docker Image') {
            steps {
                echo 'Docker images created'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deployed...'
            }
        }
    }
}
