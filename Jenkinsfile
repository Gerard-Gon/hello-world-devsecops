pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Compilando el código fuente...'
                sh 'echo "Construcción completada exitosamente."'
            }
        }
        stage('Test') {
            steps {
                echo 'Ejecutando pruebas unitarias...'
                sh 'echo "Todas las pruebas pasaron."'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Desplegando la aplicación en el entorno de prueba...'
                sh 'echo "Despliegue finalizado en QA."'
            }
        }
    }
}
