pipeline {
    agent any
    stages {
        stage('fetch code'){
            steps {
                git branch: 'master', url: 'https://github.com/saurabh-cedcoss/sample-node-project.git'
            }
        }
        stage('install'){
            steps {
                bash 'npm install'
            }
        }
        stage('start'){
            steps {
                bash 'npm start'
            }
        }
    }
}