pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "fffgfgfgfgfgfgfg"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
        stage('test') {
            steps {
                echo "fgfgfgfgfgfgfgff"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}
