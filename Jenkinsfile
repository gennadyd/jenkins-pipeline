pipeline {
    agent any

    stages {
        stage('Init') {
            steps {
                script{
                    echo 'Initializing..'
                    common.setDisplayName("")
                }
            }
        }        
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
