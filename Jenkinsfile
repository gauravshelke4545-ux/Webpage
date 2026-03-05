pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/gauravshelke4545-ux/Webpage.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Webpage Project'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Webpage'
            }
        }

    }
}
