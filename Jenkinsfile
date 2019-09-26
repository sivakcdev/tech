pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'mvn clean packag'
            }
        }
        stage('Test') {
            steps {
                echo 'test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
