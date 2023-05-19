pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing.. again'
            }
        }
        stage('Clone bis') {
            steps {
                git url: 'https://github.com/Artmorse/my-dummy-repository-bis', branch: 'main'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
