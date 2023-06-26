pipeline {
    agent none
    stages {
        stage('Run') {
            agent {
                docker {
                    image 'python:2-alpine'
                }
            }
            steps {
                sh 'python sources/print_hello.py'
            }
        }
    }
}
