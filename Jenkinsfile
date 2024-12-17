pipeline {
    agent any

    stages {
        stage('Pipeline Build') {
            steps {
                echo 'this is build phase'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the build'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project'
            }
        }
    }
}
