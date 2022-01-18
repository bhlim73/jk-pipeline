pipeline {
    agent  any  
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
