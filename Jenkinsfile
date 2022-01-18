Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'maven:3.8.4-openjdk-11-slim' } }
    stages {
        stage('setup') {
            steps {
                input "Confirm begin build?"
            }
        }
        stage('build') {
            steps {
                bat 'mvn --version'
            }
        }
    }
}
