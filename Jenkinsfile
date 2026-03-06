pipeline {
    agent any

    stages {

        stage('Branch Info') {
            steps {
                echo "Building branch: ${env.BRANCH_NAME}"
            }
        }

        stage('Build') {
            steps {
                sh 'echo Building project'
            }
        }

    }
}
