pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git branch: 'main', credentialsId: 'ffcc93cd-32bf-47d1-b25b-aa7864b69a1b', url: 'https://github.com/parsh96/terraform-cloud.git'
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
