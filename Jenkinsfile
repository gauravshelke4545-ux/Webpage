pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/gauravshelke4545-ux/Webpage.git'
            }
        }

        stage('Build') {
            steps {
                echo "Build Successful"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy Successful"
            }
        }
    }
}
