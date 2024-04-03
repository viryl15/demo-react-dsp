pipeline {
    agent any
    tool {
        nodejs 'nodejs20'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building......'
                sh  'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing......'
                sh  'npm test'
            }
        }
        stage('Deploy / Deliver') {
            steps {
                echo 'Deploying......'
            }
        }
    }
}
