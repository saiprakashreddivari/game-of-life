pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh 'echo hello'
            }
        }
        stage('learning') {
            agent { label 'ubuntu node-1' }
            steps {
                git url: 'https://github.com/saiprakashreddivari/game-of-life.git',
                    branch: 'master'
            }
        }
    }
}