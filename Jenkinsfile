pipeline {
    agent any
    stages {
        stage("Compilar") {
            steps {
                //sh "cd src"
                //sh "cd main"
                //sh "cd jenkins"
                java DemoApplication.java
                echo 'hola mundo'
               

            }
        }
        stage("Probar") {
            steps {
                echo 'No hay tests'
            }
        }
    }
}
