pipeline {
    agent { docker { image 'python:3.14-rc-bookworm' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
