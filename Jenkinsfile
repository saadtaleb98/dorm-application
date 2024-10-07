pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'This is a simple test'
            }
        }
    }
    post {
        always {
            echo 'Pipeline has completed'
        }
    }
}
