
pipeline {
    agent any

    stages {
        stage('Check Windows and Docker') {
            steps {
                bat 'echo PATH=%PATH%'
                bat 'where cmd.exe'
                bat 'where docker.exe'
                bat 'docker.exe --version'
            }
        }
    }
}
