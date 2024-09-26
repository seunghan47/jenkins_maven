pipeline {
    agent any
    trigger { pollSCM '*/1 * * * *' }
    stages {
        stage ('Testing configuration') {
            echo 'hello world'
            sh 'sleep 10s'
        }
    }
}