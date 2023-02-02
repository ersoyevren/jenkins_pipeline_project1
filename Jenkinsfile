pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "bnvbvbvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvv"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
        stage('test') {
            steps {
                echo "vbbbbbbbbbbbbbbbbbbbbbbbbbbbb"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}
