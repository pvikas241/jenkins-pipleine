pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello, World!'
            }
        }
        stage('Greeting') {
            steps {
                echo 'Greetings from Jenkins!'
            }
        }
        stage('Message') {
            steps {
                echo 'This is a message from the Message stage.'
            }
        }
        stage('Farewell') {
            steps {
                echo 'Goodbye from Jenkins!'
            }
        }
    }

    post {
        always {
            echo 'This will always run after all stages.'
        }
        success {
            echo 'This will run only if the pipeline is successful.'
        }
        failure {
            echo 'This will run only if the pipeline fails.'
        }
    }
}
