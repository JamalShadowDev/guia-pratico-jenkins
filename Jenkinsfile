pipeline{
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                echo 'Executando Build'
            }
        }

        stage('Push Docker Image') {
            steps {
                echo 'Executando Push'
            }
        }

        stage('Deploy no Kubernetes') {
            steps {
                echo 'Executando k Applay'
            }
        }
    }

}