pipeline {
    agent any

    stages {
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
        stage('Run bash') {
            steps {
               sh '''#!/bin/bash
                 echo "hello world" 
                 sh 'chmod +x ./script.sh'
                 sh './script.sh'
                '''
            }
        }
    }
}
