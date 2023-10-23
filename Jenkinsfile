pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Fikret Building..'
                nodejs(''){
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
