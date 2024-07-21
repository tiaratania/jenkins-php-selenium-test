pipeline {
    agent none
    stages {
        stage('Test Docker') {
            agent {
                docker { image 'maven:3-alpine' }
            }
            steps {
                sh 'echo "Running inside Docker"'
            }
        }
    }
}
