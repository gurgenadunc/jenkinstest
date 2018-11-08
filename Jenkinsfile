pipeline {
    agent any
    stages {
        stage('Testtt') {
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
