pipeline {
    agent any
    stages {
        stage('Run script.sh') {
            steps {
                sh 'chmod 700 script.sh'
                sh './script.sh'
            }
        }
    }
}
