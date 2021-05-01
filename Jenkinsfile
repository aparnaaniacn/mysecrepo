pipeline {
    agent any
    stages {
        stage('build master') {
            when {
                branch 'master'
            }
            steps {
                echo "Building master"
            }
        }
        stage('build dev') {
            when {
                branch 'dev'
            }
            steps {
                echo "Building dev"
            }
        }
    }
}
