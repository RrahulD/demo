pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                echo 'Version : $Version'
            }
        }
        stage('Prepare Build') {
            steps {
                echo 'Preparing Build'
                echo 'Version : $Version'
            }        
        }
        stage('Test') {
            steps {
                echo 'Testing'
                echo 'Version : $Version'
            }        
        }
        stage('Deploy') {
            steps {
                echo 'Deployed'
                echo 'Version : $Version'
            }        
        }
    }
}
