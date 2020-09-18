pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '''javac Main.java'''
                  }
        }
        stage('Test') {
            steps {
                sh '''echo "starting testing"
				java Main
				echo "testing finished"'''
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Finished'
            }
        }
    }
}
