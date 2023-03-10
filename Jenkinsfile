pipeline {
    agent any

    stages {
        stage('install-zabbix') {
            steps {
                echo 'bajando fuentes'
                git branch: 'main', url: 'https://github.com/ivanmunozm/zabbix.git'
            }
        }
    }
}