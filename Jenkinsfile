pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Hello Jenkins 👋'
                echo 'code is built'
            }
        }
        stage('test') {
            steps {
                echo 'test is success'
            }
        }
    }

    post {
        success {
            echo 'Pipeline finished successfully ✅'
        }
        failure {
            echo 'Pipeline failed ❌'
        }
    }
}
