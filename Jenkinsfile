pipeline {
    agent any

    stages {
        stage('install-zabbix') {
            steps {
                echo 'bajando fuentes'
                git branch: 'develop', url: 'https://github.com/ivanmunozm/zabbix.git'
            }
        }
        stage(){
            steps {
                echo 'Instalando zabbix'
            }
        }
    }
}