pipeline {
    agent any
    stages {
        stage('download') {
            steps {
                sh '''
                ls
                echo "hola download"
                '''
            }
        }
        stage('compilar') {
            steps {
                sh '''
                pwd
                echo "hola mundo compiler"
                '''
            }
        }
        stage('deployar') {
            steps {
                sh '''
                echo "hola mundo deployed"
                '''
            }
        }
    }
}
