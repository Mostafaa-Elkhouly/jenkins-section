pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Hello build'
            }
        }
        
        stage('test') {
            steps {
                echo 'Hello test stage'
            }
        }
        
        stage('deploy') {
            steps {
                sh 'pwd'
                sh 'whoami' 
            }
        }
    }
}
