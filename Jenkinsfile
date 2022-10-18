pipeline {
    agent NODE1
    stages {
        stage('reddy') { 
            steps {sh 'mvn package'


            }
        }
        stage ('git') { 
            steps {
                git credentialsId: 'UBUNTU', url: 'https://github.com/saiprakashreddivari/game-of-life.git',
                 
         
       
            }
        }
    }
}