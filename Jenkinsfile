pipeline {
    agent any
    tools {
        //gradle 'Gradle-7.4'
        maven 'Maven-3.8.4'
    }
    stages {
        stage ('Build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
