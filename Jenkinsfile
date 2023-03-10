pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                echo 'bajando fuentes'
                git branch: 'develop', url: 'https://github.com/ivanmunozm/zabbix.git'
            }
        }
        stage('verificar herramientas'){
            steps {
                sh '''
                  docker version
                  docker info
                  docker compose version
                  curl --version
                '''
            }
        }
        stage('docker'){
            steps {
                echo 'Instalando zabbix'
                //sh 'docker-compose up -d'
            }
        }
    }
}