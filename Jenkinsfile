pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'eject; exit 1'
            }
        }
    }
    post {
        always {
            junit 'build/reports/**/*.xml'
        }
    }
}
