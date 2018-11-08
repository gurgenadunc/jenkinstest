pipeline {
    agent any
    stages {
        stage('Testt') {
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
