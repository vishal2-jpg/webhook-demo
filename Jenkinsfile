pipeline {
    agent any

    stages {
        stage('Webhook Trigger Demo') {
            steps {
                echo 'Webhook triggered Jenkins!'
                echo 'GitHub code received successfully.'

                sh 'cat index.html'
            }
        }
    }

    post {
        success {
            echo 'Build completed successfully!'
        }
    }
}
