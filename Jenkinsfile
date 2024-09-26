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
        stage ('build mvn') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}