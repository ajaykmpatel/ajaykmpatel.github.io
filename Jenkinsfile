pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building portfolio...'
            }
        }
        stage('Test') {
            steps {
                sh 'test -f index.html'
                echo 'Success: index.html exists!'
            }
        }
    }
}
