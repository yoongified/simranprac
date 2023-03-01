pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hexmfllo Build'
            }
        }
      stage('Test') {
            steps {
                echo 'Hello Test'
            }
        }
      stage('Deloy') {
            steps {
                echo 'Hello Deploy.'
            }
        }
    }
    post{
        always{
            emailext body: 'THIS IS GIT', subject: 'HEY', to: 'shettigar269@gmail.com'
        }
    }
}
