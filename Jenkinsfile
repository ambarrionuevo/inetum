// Pipeline declarativo
pipeline {
    
    // Ejecutar desde cualquier agente (nodo) disponible
    agent any
    
    // Fases
    stages {
        stage("Fase 1 - Build") {
            // Passos de la fase
            steps {
                echo "Building artifact"
            }
        }
        stage("Testing") {
            // Passos de la fase
            steps {
                echo "Test Unitarios..."
                echo "Test Integración..."
                echo "Test Aceptación..."
            }
        }
        stage("Deploy") {
            // Passos de la fase
            steps {
                echo "Deploying artifact!!!!"
            }
        }
    }
}
