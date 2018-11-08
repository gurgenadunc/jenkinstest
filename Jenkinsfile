pipeline {
    agent any
    stages {
        stage('Tes') {
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
