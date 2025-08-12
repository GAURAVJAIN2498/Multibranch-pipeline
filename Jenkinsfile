pipeline {
    agent any
    stages {
        stage('Run script.sh') {
            steps {
                sh 'chmod 400 script.sh'
                sh './script.sh'
            }
        }
    }
}
