pipeline {
    agent any
    stages {
        stage("Compilar") {
            steps {
                //sh "cd src"
                //sh "cd main"
                //sh "cd jenkins"
                sh "java DemoApplication.java"
            }
        }
        stage("Probar") {
            steps {
                echo 'No hay tests'
            }
        }
    }
}
