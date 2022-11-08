pipeline {
    agent any
    stages {
        stage ('Clone') {
            steps {
                git credentialsId: 'global', url: 'https://github.com/vohoang1711/jenkins-github.git'
            }
        }
    }
}
