pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('testing') {
            steps {
                echo 'testing the project...'
            }
        }
        stage('deploy') {
            steps {
                echo 'Running deployment...'
            }
        }
    }

    post {
        always {
            echo 'all done!'
        }
        success {
            echo 'Pipeline executed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
