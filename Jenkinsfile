pipeline {
    agent any

    stages {
        stage('Build & Test') {
            parallel {
                stage('Windows') {
                    steps {
                        echo 'Building on Windows'
                        sh 'sleep 5'
                    }
                }
                stage('Ubuntu') {
                    steps {
                        echo 'Building on Ubuntu'
                        sh 'sleep 5'
                    }
                }
            }
        }
    }
}
