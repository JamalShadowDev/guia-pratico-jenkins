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
            when {
                branch 'main'
            }
            steps {
                echo 'Executando k Applay'
            }
        }
    }

}