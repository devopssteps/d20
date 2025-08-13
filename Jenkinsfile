@Library('myLib') _

pipeline {
    agent any

    stages {
        stage('Greet') {
            steps {
                sayHello('rajiv')
            }
        }

        stage('Status') {
            steps {
                script {
                    org.example.Utilities.printStatus("Build Successful")
                }
            }
        }
    }
}
