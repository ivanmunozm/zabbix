pipeline {
    agent any

    stages {
        stage('install-zabbix') {
            steps {
                echo 'Hello World'
                git url: 'https://github.com/ivanmunozm/zabbix.git', branch: 'main'
            }
        }
    }
}