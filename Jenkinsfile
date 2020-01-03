pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('build') {
            steps {
                echo 'in test1'
                sh 'npm --version'
            }
        }
    }
}
