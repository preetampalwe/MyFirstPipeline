pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('build') {
            steps {
                echo 'In test branch'
                sh 'npm --version'
            }
        }
    }
}
