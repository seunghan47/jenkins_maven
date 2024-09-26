pipeline {
    agent any
    triggers { pollSCM '*/1 * * * *' }
    stages {
        stage ('Testing configuration') {
            steps {
                echo 'hello world'
                sh 'sleep 10s'
            }
        }
    }
}