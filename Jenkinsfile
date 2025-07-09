pipeline {
    agent any
    stages {
        stage('Construcción') {
            steps {
                echo 'Construyendo...'
            }
        }
        stage('Verificación') {
            steps {
                echo 'Verificando HTML...'
                sh 'ls -la'
            }
        }
        stage('Despliegue simulado') {
            steps {
                echo 'Despliegue simulado completado.'
            }
        }
    }
}
