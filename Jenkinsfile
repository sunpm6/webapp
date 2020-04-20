pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            steps {
                echo "Building...!!"
                sh 'ls -l'
                sh 'mvn3 clean package'
            }
        }
        stage('Test'){
            steps {
                echo "Testing...!!"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying...!!!"
                
        }
    }
}