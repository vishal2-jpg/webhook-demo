
pipeline {
    agent any

    stages {
        stage('Webhook Test') {
            steps {
                echo 'GitHub webhook triggered Jenkins!'
                echo 'Pipeline executed successfully!'
                sh 'date'
            }
        }
    }

    post {
        success {
            echo 'Build SUCCESS!'
        }
        failure {
            echo 'Build FAILED!'
        }
    }
}
