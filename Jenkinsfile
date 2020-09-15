pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                javac Main.java
                  }
        }
        stage('Test') {
            steps {
                java Main
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Stage'
            }
        }
    }
}
