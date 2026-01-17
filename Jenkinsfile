pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/Rayhan-abdullha/jenkins-p.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}

