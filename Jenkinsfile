pipeline {
    agent any

    stages {
        stage('install-zabbix') {
            steps {
                echo 'Hello World'
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/ivanmunozm/zabbix.git']])
            }
        }
    }
}