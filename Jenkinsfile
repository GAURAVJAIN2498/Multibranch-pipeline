pipeline {
    agent any
    stages {
        stage('Run script.sh') {
            steps {
                sh 'sudo chmod 700 script.sh'
                sh './script.sh'
            }
        }
    }
}
