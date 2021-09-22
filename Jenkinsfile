pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                echo "Ejecutando Script creado en Jenkins"
                sh '''
                    sh FirstScript.sh 
                '''
            }
        }
    }
}
