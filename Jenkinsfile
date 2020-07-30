pipeline {
    agent any

    stages {
        stage('Init') {
            steps {
                script{
                    echo 'Initializing..'
                    common.setDisplayName("PipelineTest")
                    job_params = readJSON file: "./params.json"
                    println job_params

                    sh "ls -ltr"

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
