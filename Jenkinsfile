pipeline {
    agent any
    stages {
        stage("Compilar") {
            steps {
                sh 'javac holamundo.java'
                sh 'java holamundo.'
                echo 'ey'
             

            }
        }
        stage("Probar") {
            steps {
                echo 'No hay tests'
            }
        }
    }
}
