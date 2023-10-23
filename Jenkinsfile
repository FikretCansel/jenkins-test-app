pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Fikret Building..'
                nodejs('Node-18.18.2'){
                    sh 'yarn install'
                    sh 'yarn run test'
                }
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
