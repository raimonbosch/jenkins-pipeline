pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                build job: 'build'
            }
        }
        stage('generate') {
            steps {
                build job: 'generate'
            }
        }
        stage('test') {
            steps {
                build job: 'test'
            }
        }
        stage('deploy'){
            steps {
                build job: 'deploy'
            }
        }
    }
}
